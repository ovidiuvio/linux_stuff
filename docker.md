### Docker file explained
[Dockerfile](https://docs.docker.com/engine/reference/builder/)
### Docker Entrypoint explained
[Entrypoint](https://medium.com/the-code-review/how-to-use-entrypoint-with-docker-and-docker-compose-1c2062aa17a2)

### Snippets

### Get container id
```
sudo docker container ps
```
### Attach to a running container
```
sudo docker exec -i -t <id> /bin/bash
```
### Stop container
```
sudo docker stop <id>
```
### Modify entrypoint
```
sudo docker run -t --entrypoint=sh
```
### Stop all containers
```
sudo docker stop $(docker ps -q)
```




