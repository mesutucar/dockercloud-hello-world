hello-world
===========

[![Deploy to Docker Cloud](https://raw.githubusercontent.com/mesutucar/dockercloud-hello-world/master/first-service-webpage.png)](https://cloud.docker.com/stack/deploy/)

Sample docker image to test docker deployments

## Running locally

Build and run using Docker Compose:

	$ git clone https://github.com/docker/dockercloud-hello-world
	$ cd dockercloud-hello-world
	$ docker-compose up


## Deploying to Docker Cloud

[Install the Docker Cloud CLI](https://docs.docker.com/docker-cloud/tutorials/installing-cli/)

	$ docker login
	$ docker-cloud stack up

Hello world!

## Configuration

|Environment Variable|Default|Description|
|:-----:|:-----:|:----------|
|LISTEN_PORT|80|Set the Listen Port to access the hello-world container if it has the same Service Port.
