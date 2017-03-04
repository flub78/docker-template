# flub78/template

Dockerfile and environment to build a template docker container

## Build
docker build -t flub78/template .

## Usage
to start
docker run -d --name=template flub78/template

or docker-compose up -d

to stop
docker kill template
docker rm -f template

to login
docker exec -ti flub78/template /bin/bash

## Services 

http://localhost:7080/info.php
