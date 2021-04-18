# zeppelin

Minimal working Docker image of Apache Zeppelin 0.9.0 for python notes.
Many things are get removed from the image to reduce the size.

## Build image

```docker build -t zeppelin:0.9.0 .```

## Start zeppelin

```docker run --rm -p 8080:8080 zeppelin:0.9.0```