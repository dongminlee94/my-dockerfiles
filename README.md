# My Dockerfiles

## Requirements

This repository is implemented and verified on **python 3.8**.

## Installation

```bash
$ make init
```

## How to Run

### Docker Build

```bash
$ docker build -f docker/base/Dockerfile . -t base-cpu
```

### Docker Run

```bash
$ docker run -it -d -p 8888:8888 --name=base-cpu base-cpu
```

### Docker Exec

```bash
$ docker exec -it base-cpu /bin/bash
```

### Docker Inspect

```bash
$ docker inspect base-cpu
```