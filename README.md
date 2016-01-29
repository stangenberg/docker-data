# Docker data
Docker data container.

[![Docker Stars](https://img.shields.io/docker/stars/stangenberg/data.svg)][dockerhub] [![Docker Pulls](https://img.shields.io/docker/pulls/stangenberg/data.svg)][dockerhub] [![Image Size](https://img.shields.io/imagelayers/image-size/stangenberg/data.svg)](https://imagelayers.io/?images=stangenberg/data) [![Image Layers](https://img.shields.io/imagelayers/layers/stangenberg/data.svg)](https://imagelayers.io/?images=stangenberg/data)

## Features
An empty docker container to store data.

## Exposed volumes
None.

## Exposed ports
None

## Environment Variables
None.

## Usage
Use it as data container that is linked to other containers.

## Build
Make is used as build system.
- `make` / starts normal docker build.
- `make run` / build and run the container. This uses `data` as container name and automatically stops a running container with an equal name beforehand.
- `make bash` /  build, run the container and start a bash prompt.
- `make ncbuild` / normal build without using the docker cache ( --no-cache ).

[Docker Build Reference https://docs.docker.com/reference/builder/](https://docs.docker.com/reference/builder/)

## License
[Published under the MIT License][LICENSE]

[dockerhub]: https://hub.docker.com/u/stangenberg/data
[license]: https://github.com/stangenberg/docker-data/blob/master/LICENSE.md
