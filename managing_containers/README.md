 
## Managing Containers
Easily create, run, stop, and remove containers with these commands:

- `docker run hello-world`  | "Run a test container."
```bash
    docker run hello-world
```
![image](assets/Screenshot1.png)

- `docker ps`  | "List running containers."
```bash

```
- `docker ps -a` | "List **all** containers (including stopped ones)."
```bash

```
- `docker stop <container_id>` | "Stop a running container."
- `docker start <container_id>` "Start a stopped container."
- `docker restart <container_id>`  | "Restart a container."
- `docker rm <container_id>`  | "Remove a container."
- `docker logs <container_id>` | "View logs of a container."
- `docker exec -it <container_id> /bin/bash` "Access a container’s interactive shell."
