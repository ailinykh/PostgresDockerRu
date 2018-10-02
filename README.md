# PostgresDockerRu
Контейнер PostgreSQL с установленной русской локалью

## Build
For local build use command

```bash
docker build .
```

## Dockerhub
For production use build with tag

```bash
docker build . -t <your_dockerhub_name>/<your_dockerhub_repo>
docker push <your_dockerhub_name>/<your_dockerhub_repo>
```

You all set!
