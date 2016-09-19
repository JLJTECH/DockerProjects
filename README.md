# DockerProjects
Collection of Docker related projects

##Show running containers
```docker ps```

##Stop all running Containers:
```docker stop $(docker ps -a -q)```

##Remove all Containers:
```docker rm $(docker ps -a -q)```

##Remove all Images:
```docker rmi $(docker images -q)```
