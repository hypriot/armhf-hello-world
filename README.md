# About this repo

This is the repo for the armhf compatible clone of the [hello-world](https://github.com/docker-library/hello-world) Docker image.
It is used in the Docker integration tests.

To create an new version of the `hello` binary run in the root of this directory (eg. in boot2docker):

```
docker run --rm -v $(pwd)/src:/src ubuntu:14.04 bash -c "cd /src && ./fasmarm hello.fasm"
```
