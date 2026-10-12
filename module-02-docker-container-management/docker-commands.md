# Module 2: Docker Image & Container Management

## Objective
Learn Docker image management and container lifecycle operations.

## 1. Download Nginx Image
Command: docker pull nginx:stable

Purpose: Downloads the stable Nginx image.

## 2. Verify Image
Command: docker images

Purpose: Lists downloaded Docker images.

## 3. Run Container
Command:
docker run -d --name module2-nginx-stable -p 8081:80 nginx:stable

Purpose: Runs an Nginx container in detached mode.

## 4. Verify Container
Command: docker ps

Purpose: Lists running containers.

## 5. Test Web Server
URL: http://localhost:8081

Purpose: Verifies Nginx deployment.

## 6. Inspect Container
Command: docker inspect module2-nginx-stable

Purpose: Displays container configuration.

## 7. View Logs
Command: docker logs module2-nginx-stable

Purpose: Displays container logs.

## 8. Stop Container
Command: docker stop module2-nginx-stable

Purpose: Stops the running container.

## 9. Start Container
Command: docker start module2-nginx-stable

Purpose: Restarts the stopped container.

## Result
A stable Nginx image was used to deploy and test a Docker container.
