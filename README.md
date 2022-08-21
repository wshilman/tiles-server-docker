# Tiles Server Docker
This repository contains 2 main things:
- A `docker-compose.yml` file with the services to build and deploy
- A folder /data which contains
 - A `config.json` file, which contains the configuration of the layers to be served by the tile server
 - The .mbtiles layers, to be served by the tile server

## Pre-requisites
To install the mapserver, it is needed in the host machine
- Git
- Docker
- Docker-compose

## Installation
To install the mapserver (in linux or mac), simply run bash `run_tileserver.sh`

Then, to run it simply use `docker-compose up -d` to start
and `docker-compose down` or `docker-compose stop` to stop the service

The `docker-compose up` command also build it. So if you are in windows, you can just execute those commands

## About
![Maptiler logo](https://www.maptiler.com/styles/style/logo/maptiler-logo-adaptive.svg?123#maptilerLogo)

Vector and raster maps with GL styles. Server-side rendering by Mapbox GL Native. Map tile server for MapLibre GL JS, Android, iOS, Leaflet, OpenLayers, GIS via WMTS, etc.

For this repository, we are using the official image of maptiler/tileserver-gl in [Docker Hub](https://hub.docker.com/r/maptiler/tileserver-gl)

## Documentation
You can read full documentation of this project at https://tileserver.readthedocs.io/