# Command for the docker

[Official documentation](https://docs.docker.com/)

## Main commands

```shell
docker image ls #get all the image
docker container ls # get all the active container
docker stop $(docker ps -a -q) # Stop all containers
docker rm $(docker ps -a -q) # Delete all container
docker rmi $(docker images -q) # Delete all images
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
