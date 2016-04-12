# docker-angularjs-container (Docker Container)

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

## Removing container
```
docker rm -f angularjs-01
```

## Container based on
* [ubuntu:14.04](https://hub.docker.com/_/ubuntu/)

## Bundled Software:
* [Nginx](https://www.nginx.com/) a web server
* [Node.js](https://nodejs.org/en/) a JavaScript runtime
* [Bower](http://bower.io/) a package manager
* [Less](http://lesscss.org/) a CSS pre-processor
* [watch-less](https://www.npmjs.com/package/watch-less) a command line

## Copyright and license:
This project is licensed under Apache License Version 2 see 
the [LICENSE](https://github.com/mlatzko/docker-angularjs-container/blob/master/LICENSE) file.

## Hat-Tip
* [@amandiel](https://github.com/amandiel)
