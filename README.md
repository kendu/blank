# Blank image

Primary use is for running go binaries.
The expected use is to use the docker-compose.
```
goapp
  volumes:
    - /path/to/go/binary:/mount/path
  expose:
    - <port to expose>
  command: /path/to/mounted/binary
```

It can also be used to build images.
