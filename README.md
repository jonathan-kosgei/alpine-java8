# Alpine Java8

**_Image size:_** 72 mb

## Getting Started

To use this image run

```
docker pull jkosgei/alpine-java8
```

To use this image as a base for you java8 dependent application, use

```
FROM jkosgei/alpine-java8
...
```

## Dockerfile

```
FROM alpine:3.6

RUN apk add --no-cache openjdk8

```