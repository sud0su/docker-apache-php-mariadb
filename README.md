# Nginx-MariaDB-PHP

Use docker to run local server without install LAMPP.

## Setup

- Install `docker`.

- Create folder www for root project.

### Run docker

```console
sud0su@oprek$ docker-compose up -d
```

#### Check container running

```console
sud0su@oprek$ docker ps
```

#### Running MySQL shell command line

```console
sud0su@oprek$ docker-compose exec mysql sh
```

### Stop docker

```console
sud0su@oprek$ docker-compose stop
```

### Remove all docker image

```console
sud0su@oprek$ docker-compose rm --all
```
