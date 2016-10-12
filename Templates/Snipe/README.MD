#Snipe App Base Config

##The following are prereqs
- Post pre config and mysql linking from basic installation instructions 
- Generated App key with ```docker run snipe/snipe-it```
- .ENV file created and hosted in project root
  - Database credentials, ports and app key added
- mySql container running
- port Mapping 8080


###Start the environment with the following
```
docker run --link snipe-mysql:mysql -d -p 8080:80 --name=snipe-it --env-file mysnipe.env snipe/snipe-it
```
