# Test in local docker env

You can test locally using docker.

dependencies

- docker
- docker-compose

## how to use

```
$ cd ./unity-nginx/docker

// start container
$ docker-compose up -d
```

then, access http://localhost:80

other commands:
```
// stop container
$ docker-compose stop

// down
$ docker-compose down

// build
$ docker-compose build

// log
$ docker-compose logs -f
```