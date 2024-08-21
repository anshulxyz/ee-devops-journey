# fastapi-hello-world

### to build

```
docker build -t fastapi-hello:latest .
```
### to run
```
docker run -p 8080:80 fastapi-hello:latest
```
And then visit http://localhost:8080/

### notes

- `-p HOST_PORT:CONTAINER_PORT`, refer [publishing ports](https://docs.docker.com/guides/docker-concepts/running-containers/publishing-ports/#publishing-ports)
