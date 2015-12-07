# Docker data

Docker data container.

Dockerhub: [stangenberg/data][dockerhub]

## Features ##

An empty docker container o store data.


## Exposed volumes ##

None.


## Exposed ports ##

- 22 / SSH


## Environment Variables

None.


## Usage ##

Use it as data container that is linked to other containers.


## Build

Make is used as build system.

- `make` / starts normal docker build.
- `make run` / build and run the container. This uses `data` as container name and automatically stops a running container with an equal name beforehand.
- `make bash` /  build, run the container and start a bash prompt.
- `make ncbuild` / normal build without using the docker cache ( --no-cache ).

[Docker Build Reference https://docs.docker.com/reference/builder/](https://docs.docker.com/reference/builder/)


## License ##

[Published under the MIT License][LICENSE]

[DOCKERHUB]: https://hub.docker.com/u/stangenberg/data
[LICENSE]: https://github.com/stangenberg/docker-data/blob/master/LICENSE.md
