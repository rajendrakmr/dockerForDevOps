## Docker Network
Quickly manage networks: create, connect, inspect, and remove.

*Example output of running `network ls`.*
   - `docker network ls`  - "List all networks"
```bash
   docker network ls 

 ```
![Docker Run Screenshot1](../assets/networks/Screenshot1.png)  
    

*Example output of running `create`.*
   - ` docker network create <network-name>`  - "Create a custom network"
```bash
    docker network create mynetwork 

 ```
![Docker Run Screenshot2](../assets/networks/Screenshot2.png)  
    

*Example output of running `login`.*
   - `docker run --network=mynetwork nginx`  - "Attach container to network"
```bash
    docker run --network=mynetwork nginx

 ```
![Docker Run Screenshot3](../assets/networks/Screenshot3.png)  


*Example output of running `push`.*
   - `docker network inspect <network-name>` - "Inspect network details"
```bash
   docker network inspect mynetwork

```
![Docker Run Screenshot4](../assets/networks/Screenshot4.png)  
![Docker Run Screenshot5](../assets/networks/Screenshot5.png)    



*Example output of running `rmi`.*
   - `docker network rm <network-name>`   "Remove an image"
```bash
   docker network rm mynetwork
```
![Docker Run Screenshot7](../assets/networks/Screenshot7.png)    

