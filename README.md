# Alpine Core

## Description

Base alpine-core with customizations for building and running containers.
This container does not do anything on its own, it is just a baseline used to
build other containers.

This container can be used by the following commands:

## Note / Disclaimer

This isn't the best method to run multiple services. For kubernetes you create
a manifest with multiple containers in the same pod. For docker, it is best to
use a docker-compose file to handle multiple containers/services at once.

## Usage

```bash
docker pull ghcr.io/dragons-rage/alpine-core:latest
```

or

```bash
docker pull faliarin/alpine-core:latest

```

## Links

- [Repo](https://github.com/dragons-rage/alpine-core)
- [S6 Overlay](https://github.com/just-containers/s6-overlay)
