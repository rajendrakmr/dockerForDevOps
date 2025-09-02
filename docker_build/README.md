## Build Images
Quickly manage Docker images: build, push, tag, and rmi them.

*Example output of running `build`.*
   - `docker build -t <image-name>`  - "Build image from Dockerfile in current directory"
```bash
   docker build -t mybackend . 

 ```
![Docker Run Screenshot1](../assets/build/Screenshot1.png)  
    

*Example output of running `tag`.*
   - ` docker tag old-image newimage:1.0`  - "Rename or version an image"
```bash
    docker tag mybackend:latest rk0617/mybackend:latest
    docker tag mybackend rk0617/mybackend:latest

 ```
![Docker Run Screenshot2](../assets/build/Screenshot2.png)  
    

*Example output of running `login`.*
   - `docker login -u <username>`  - "Logged in to your docker hub."
```bash
    docker login -u rk0617 

 ```
![Docker Run Screenshot3](../assets/build/Screenshot3.png)  


*Example output of running `push`.*
   - `docker push <image-name>:<image-tag/version>` - "Push image to Docker Hub"
```bash
   docker push rk0617/mybackend:latest
```
![Docker Run Screenshot4](../assets/build/Screenshot4.png)  
![Docker Run Screenshot5](../assets/build/Screenshot5.png)    



*Example output of running `rmi`.*
   - `docker rmi <image_id> `   "Remove an image"
```bash
   docker rmi af677e77d360 
```
![Docker Run Screenshot3](../assets/images/Screenshot3.png)  
   

