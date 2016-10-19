## Docker Node Server ##

The docker node server creates a container with the starter necessary tools for begin your node application.

# To Run the environment #
```sh
docker-compose up -d
```

# Run without docker-compose #
```sh
docker run -it -d -f config/docker/node/Dockerfile -p 1703:8080 -v $PWD/src:/usr/src/app
```

# Ports #
By default the port that use with this repo is the port *'1703'* you always can change for other in the docker-compose.yml
