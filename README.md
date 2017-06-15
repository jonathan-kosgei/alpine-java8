# Alpine Java8

## Getting Started

To use this image run

```
docker pull jkosgei/java8:alpine-java:8
```

To use this image as a base for you java8 dependent application, use

```
FROM jkosgei/java8:alpine-java:8
...
```

## Dockerfile

```
FROM alpine:3.6

RUN apk add --no-cache openjdk8

```