# host-visitor-count
A simple docker repo that host visitor count on redis


# Commands
##Single Image from Dockerfile
```
$ docker build -t host-visitor-count .

$ docker image ls
$ docker container ls
$ docker run -p 4000:80 host-visitor-count
$ docker run -d -p 4000:80 host-visitor-count

$ docker login
$ docker tag host-visitor-count:latest dvdhinesh/host-visitor-count:latest
$ docker push dvdhinesh/host-visitor-count

$ docker run -p 4000:80 dvdhinesh/host-visitor-count
```

##Multi Image from Docker Compose file
```

```

## Utility
```
$ docker ps
$ docker ps -a

$ docker --version
$ docker info
$ docker version

$ docker image ls

$ docker container --help
$ docker container
$ docker container ls
$ docker container ls --all
$ docker container ls -aq

$ docker exec -it <Container NAME or ID> /bin/bash
$ docker container stop <Container NAME or ID>
$ docker rmi <IMAGE ID>
```
