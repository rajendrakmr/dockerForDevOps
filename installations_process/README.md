 
## Managing Containers
Easily create, run, stop, and remove containers with these commands:

- docker run hello-world   "Run a test container."
 

- `docker ps`  
  List running containers.

- `docker ps -a`  
  List **all** containers (including stopped ones).

- `docker stop <container_id>`  
  Stop a running container.

- `docker start <container_id>`  
  Start a stopped container.

- `docker restart <container_id>`  
  Restart a container.

- `docker rm <container_id>`  
  Remove a container.

- `docker logs <container_id>`  
  View logs of a container.

- `docker exec -it <container_id> /bin/bash`  
  Access a container’s interactive shell.
