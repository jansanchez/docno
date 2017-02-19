# Docker Commands

## list docker images
```
docker images
```

## Build an image
```
docker build -t {newImageName} .
```

## Run a Docker image
```
docker run -p {clientPort}:{serverPort} -d {imageName}
```

## Remove a container
```
docker rm {containerName}
```

## Remove an docker image
```
docker rmi {imageName}
```

## List docker containers
```
docker ps
```

## To go inside the container
```
docker exec -it {containerID} /bin/bash
```

## Kill one or more running containers
```
docker kill {containerID}
```
