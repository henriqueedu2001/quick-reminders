List running containers
```bash
docker ps
```

Run a container from an image
```bash
docker run <image_name>
```

Stop a container
```bash
docker stop <container_id>
```

Remove a container
```bash
docker rm <container_id>
```

List local images
```bash
docker images
```

Build an image from a Dockerfile
```bash
docker build -t <image_name> .
```

Execute a command inside a running container
```bash
docker exec -it <container_id> <command>
```

Remove an image
```bash
docker rmi <image_id>
```