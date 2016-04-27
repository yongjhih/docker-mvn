# docker-mvn

[![Docker Pulls](https://img.shields.io/docker/pulls/_/maven.svg)](https://hub.docker.com/r/_/maven/)
[![Docker Stars](https://img.shields.io/docker/stars/_/maven.svg)](https://hub.docker.com/r/_/maven/)
[![Docker Size](https://img.shields.io/imagelayers/image-size/_/maven/latest.svg)](https://imagelayers.io/?images=_/maven:latest)
[![Docker Layers](https://img.shields.io/imagelayers/layers/_/maven/latest.svg)](https://imagelayers.io/?images=_/maven:latest)

## Usage

Install mvn wrapper:

```sh
docker run -it --rm -v "$PWD":/src -w /src maven mvn -N io.takari:maven:wrapper
```

Install mvn wrapper 3.3.3:

```sh
docker run -it --rm -v "$PWD":/src -w /src maven mvn -N io.takari:maven:wrapper -Dmaven=3.3.3
```
