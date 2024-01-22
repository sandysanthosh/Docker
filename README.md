# Docker

Certainly! Here are some common Docker commands to get you started:

1. **Build an image from a Dockerfile:**
   ```bash
   docker build -t image_name:tag .
   ```

2. **Run a container from an image:**
   ```bash
   docker run -d --name container_name image_name:tag
   ```

3. **List running containers:**
   ```bash
   docker ps
   ```

4. **List all containers (including stopped ones):**
   ```bash
   docker ps -a
   ```

5. **Stop a running container:**
   ```bash
   docker stop container_name_or_id
   ```

6. **Start a stopped container:**
   ```bash
   docker start container_name_or_id
   ```

7. **Remove a container:**
   ```bash
   docker rm container_name_or_id
   ```

8. **Remove an image:**
   ```bash
   docker rmi image_name:tag
   ```

9. **View logs of a container:**
   ```bash
   docker logs container_name_or_id
   ```

10. **Execute a command inside a running container:**
    ```bash
    docker exec -it container_name_or_id command
    ```

11. **List Docker networks:**
    ```bash
    docker network ls
    ```

12. **Inspect a Docker network:**
    ```bash
    docker network inspect network_name
    ```

13. **Pull an image from Docker Hub:**
    ```bash
    docker pull image_name:tag
    ```

14. **Push an image to Docker Hub:**
    ```bash
    docker push image_name:tag
    ```

15. **Build and run using Docker Compose:**
    ```bash
    docker-compose up -d
    ```

These are just some basic commands to get you started. Explore the Docker documentation for more detailed information and advanced usage.
