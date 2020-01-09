# packages/golang

## Troubleshooting

`
$ docker build -t my-go-app ./packages/golang
error during connect: Post http://%2F%2F.%2Fpipe%2Fdocker_engine/v1.40/build?buildargs=%7B%7D&cachefrom=%5B%5D&cgroupparent=&cpuperiod=0&cpuquota=0&cpusetcpus=&cpusetmems=&cpushares=0&dockerfile=Dockerfile&labels=%7B%7D&memory=0&memswap=0&networkmode=default&rm=1&session=g33587ythpo2fwr8sykyb3awz&shmsize=0&t=my-go-app&target=&ulimits=null&version=1: open //./pipe/docker_engine: The system cannot find the file specified. In the default daemon configuration on Windows, the docker client must be run elevated to connect. This error may also indicate that the docker
daemon is not running.
``

Ensure the docker daemon is running on your system

## Resources

- https://tutorialedge.net/golang/go-docker-tutorial/