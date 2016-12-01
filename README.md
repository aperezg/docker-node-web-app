# Docker image for Node Express Web Server

## Tags

* latest [Dockerfile](https://github.com/aperezg/docker-node-web-app/blob/master/Dockerfile)

The docker node server creates a container with the starter necessary tools for begin your node application.

## To run

```sh
docker run --rm -p 80:8080 -v $PWD/www:/usr/src/app/www -v $PWD/package.json:/usr/src/app/package.json aperezg/docker-node-web-app:latest
```

## Run with docker compose
```yml
version: '2'
services:
    php:
        image: aperezg/docker-node-web-app
        ports:
            - 80:8080
        volumes:
            - $PWD/www:/usr/src/app/www
            - $PWD/package.json:/usr/src/app/package.json
```

# www folder #
This folder is where you add the source of your web application, is a docker volume and to start
contain the server.js to run the node server.

## Fork this repo

If you think that you can improve this image, fork this repo, and send me a pull request. I'll be happy to add your new features.

This repository is under [GNU v3.0 License](https://github.com/aperezg/docker-node-web-app/blob/master/LICENSE) 