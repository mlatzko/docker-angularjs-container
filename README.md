# docker-angularjs-container

This container enables to start developing & maintaining an AngularJS application.

## Building container
```
docker build https://github.com/iconicfuture/docker-angularjs-container.git -t docker-angularjs-container
```

## Running container
```
docker run --name angularjs-01 -p 80:80 -v "/srv/[project path]:/srv/www" -d docker-angularjs-container
```

## Connecting container
```
docker exec -it angularjs-01 /bin/bash
```

## Container based on
* [ubuntu:14.04](https://hub.docker.com/_/ubuntu/)

## Bundled Software:
* [Node.js](https://nodejs.org/en/) a JavaScript runtime
* [Bower](http://bower.io/) a package manager
* [Less](http://lesscss.org/) a CSS pre-processor