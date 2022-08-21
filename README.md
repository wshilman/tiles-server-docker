# tiles-server-docker
This repository contains 2 main things.
A `docker-compose.yml` file with the services to build and deploy
A folder /data which contains
- A `config.json` file, which contains the configuration of the layers to be served by the tile server
- The .mbtiles layers, to be served by the tile server

## Pre-requisites
To install the mapserver, it is needed in the host machine
- Git
- Docker
- Docker-compose

## Installation
To install the mapserver, simply run ./run.sh