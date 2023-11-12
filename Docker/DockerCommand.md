# Command for the docker

[Official documentation](https://docs.docker.com/)

## Main commands

```shell
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker rmi $(docker images -q)
```

If the build in note in the same folder (parameter -t) and src in context

```shell
docker build -t statistics-api-image -f build/Dockerfile ./src/
```

Call the docker compose file

```shell
docker-compose up -d
```

[docker-compose example](./docker-compose.exemple.yml)\
In this example, we have the MongoDb and kafka creation (with topic init)
