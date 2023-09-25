# docker-learning-notes-commands
Docker related learning notes and commands

Certainly! Here's a list of some commonly used Docker commands along with brief explanations of what each command does:

1. **docker run**:
   - **Explanation**: This command is used to create and start a new container from a Docker image. You specify an image, and Docker creates an instance of it as a running container.
   - **Example**: `docker run -d -p 8080:80 nginx` (Runs an Nginx web server in the background, mapping port 8080 on your computer to port 80 in the container.)

2. **docker build**:
   - **Explanation**: This command is used to build a Docker image from a Dockerfile, which contains instructions for creating an image with your application and its dependencies.
   - **Example**: `docker build -t myapp .` (Builds an image named "myapp" from the Dockerfile in the current directory.)

3. **docker pull**:
   - **Explanation**: This command is used to download a Docker image from a registry (like Docker Hub) to your local machine.
   - **Example**: `docker pull ubuntu` (Downloads the latest Ubuntu image.)

4. **docker images**:
   - **Explanation**: This command lists all the Docker images that are available on your local machine.
   - **Example**: `docker images` (Lists all locally available images.)

5. **docker ps**:
   - **Explanation**: As mentioned earlier, this command lists the running containers on your system.
   - **Example**: `docker ps` (Lists running containers.)

6. **docker stop**:
   - **Explanation**: This command stops a running container. You provide either the container's name or its ID.
   - **Example**: `docker stop my-container` (Stops the container named "my-container".)

7. **docker start**:
   - **Explanation**: This command starts a stopped container.
   - **Example**: `docker start my-container` (Starts the previously stopped container named "my-container".)

8. **docker restart**:
   - **Explanation**: This command restarts a running or stopped container.
   - **Example**: `docker restart my-container` (Restarts the container named "my-container".)

9. **docker rm**:
   - **Explanation**: This command removes one or more stopped containers. You specify either container names or IDs.
   - **Example**: `docker rm my-container` (Removes the stopped container named "my-container".)

10. **docker rmi**:
    - **Explanation**: This command removes one or more Docker images from your local machine.
    - **Example**: `docker rmi my-image` (Removes the Docker image named "my-image".)

11. **docker exec**:
    - **Explanation**: This command allows you to run a command inside a running container. You specify the container's name or ID and the command to run.
    - **Example**: `docker exec -it my-container bash` (Starts a shell session inside the running container "my-container".)

12. **docker-compose**:
    - **Explanation**: This is a command-line tool for defining and running multi-container applications using a Docker Compose YAML file.
    - **Example**: `docker-compose up` (Starts the services defined in the `docker-compose.yml` file.)

These are some of the fundamental Docker commands that you'll use frequently when working with Docker containers and images. There are many more Docker commands and options available, which you can explore further based on your specific needs and use cases.


