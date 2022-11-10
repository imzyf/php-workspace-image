# My PHP Workspace Base Image

https://github.com/laradock/workspace

https://hub.docker.com/r/laradock/workspace

https://hub.docker.com/r/yifans/php-workspace/tags

- https://raw.githubusercontent.com/laradock/workspace/master/Dockerfile-7.1
- https://raw.githubusercontent.com/laradock/workspace/master/Dockerfile-7.4

- https://hub.docker.com/repository/registry-1.docker.io/yifans/php-workspace/tags?page=1&ordering=last_updated

docker build --tag yifans/php-workspace:main-7.1 -f ./Dockerfile-7.1 .

docker run --help

docker run -d fd73afb17bcb

## use

```bash
docker run -v $PWD:/var/www --rm laradock-workspace:latest php -m
docker run -v $PWD:/var/www --rm laradock-workspace:latest php -m
docker run -v $PWD:/var/www --rm yifans/php-workspace:main-7.1 php -m
```

## my

- MongoDB
- redis
- Swoole
- xlswriter
- AST
