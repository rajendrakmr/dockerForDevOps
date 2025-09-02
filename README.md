## DockerForDevOps
A Complete Docker Guide for Developers & DevOps Engineers 

- [Installation Process](installations_process/README.md)
  
- [Managing Containers](managing_containers/README.md)
```bash
  docker run hello-world          # Run a test container
  docker ps                       # List running containers
  docker ps -a                    # List all containers
  docker stop <container_id>      # Stop a running container
  docker start <container_id>     # Start a stopped container
  docker restart <container_id>   # Restart a container
  docker kill <container_id>      # Before remove kill a container
  docker rm <container_id>        # Remove a container
  docker logs <container_id>      # View logs of a container
  docker exec -it <container_id> /bin/sh # Access container shell
```

- [Managing Images](managing_images/README.md)
```bash
  docker images                   `List all images`
  docker pull nginx               `Download an image from Docker Hub`
  docker rmi <image_id>           `Remove an image`
  docker inspect <image_id>       `View detailed image info`

```
- [Docker Build](docker_build/README.md)
```bash
  docker build -t myapp .          `Build image from Dockerfile in current directory`
  docker tag old-image newimage:1.0 `Rename or version an image`
  docker push myimage:latest       `Push image to Docker Hub`
  docker rmi myapp                 `Remove local image`

```
- [Docker Compose](docker_compose/README.md)
```bash
  docker-compose up               `Start services from docker-compose.yml`
  docker-compose down             `Stop and remove services`
  docker-compose ps               `View status of services`
  docker-compose logs             `View logs of services`
  docker-compose build            `Build images defined in docker-compose.yml`

```
- [Docker Volumes](docker_volumes/README.md)
```bash
  docker volume ls                `List volumes`
  docker volume create myvolume   `Create a volume`
  docker run -v myvolume:/data nginx `Mount a volume to container`
  docker volume rm myvolume       `Remove a volume`

```
- [Docker Networks](doker_networks/README.md)
```bash
  docker network ls               `List all networks`
  docker network create mynetwork `Create a custom network`
  docker run --network=mynetwork nginx `Attach container to network`
  docker network inspect mynetwork `Inspect network details`
  docker network rm mynetwork     `Remove network`

```

