## Docker Node Server ##

The docker node server creates a container with the starter necessary tools for begin your node application.

# www folder #
This folder is where you add the source of your web application, is a docker volume and to start
contain the server.js to run the node server.

# To Run the environment #
```sh
docker-compose up -d
```

# Ports #
By default the port that use with this repo is the port *'1703'* you always can change for other in the docker-compose.yml
