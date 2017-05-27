# DockerProjects and Shortcuts
Collection of Docker related items

##Show running containers
```docker ps```

##Stop all running containers:
```docker stop $(docker ps -a -q)```

##Remove all containers:
```docker rm $(docker ps -a -q)```

##Remove all images:
```docker rmi $(docker images -q)```

##Build from Docker file using compose (file dir):
```docker-compose build```

##Run from Docker file:
```docker-compose up -d``` 

##Locate volumes on the host
```docker inspect web```
