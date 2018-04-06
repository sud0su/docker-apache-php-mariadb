# Apache-MariaDB-PHP

Use docker to run local server without install any depedencies.

## Setup

- Install `docker`

#### Run docker

```console
sud0su@opek$ docker-compose up -d
```

##### Running MySQL shell command line

```console
sud0su@opek$ docker-compose exec mysql sh
```

#### Stop docker

```console
sud0su@opek$ docker-compose stop
```

#### Remove all docker image

```console
sud0su@opek$ docker-compose rm --all
```
