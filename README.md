# armhf-hello-world

docker run --rm -v $(pwd)/src:/src ubuntu:14.04 bash -c "cd /src && ./fasmarm hello.fasm"
