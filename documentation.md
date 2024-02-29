# Day - 3
1. Installation of docker.

   Installed docker from browser.
2. checked wheather docker is installed .
   ```dockerfile
   docker --version
   ```
3. created a image .
   ```dockerfile
   docker build -t <imagename>
   ```
4. checked wheather image is created.
   ```dockerfile
   docker image ls
   
   ```
5. Moved image to docker container.
   ```dockerfile
   docker run --name <containername> <imagename>
   
   ```
6. I got error while running docker container that my container was using differnt port.
   ```dockerfile
   docker run -p <hostport>:<containerport> --name<containername><imagename>
   
   ```
    