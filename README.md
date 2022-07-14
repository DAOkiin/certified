Based on [this gist](https://gist.github.com/saniaky/dc75cbf64922e418400b0f54ed5b2c3a)

1. You need to create a docker network before
```shell
docker network create certified
```
2. Add the network and env configuration from the [example](service.docker-compose.yml) to your docker compose files 