# HelloPlay

## Launch Local

```
$ activator run
```

## Deploy Local (Docker)

```
$ activator docker:publishLocal
$ docker-compose up
```

## Deploy Production (Generate Dockerfile)

```
$ activator docker:stage
$ ls target/docker/stage
```
