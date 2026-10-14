# Module 5: Docker Networking & Container Communication

## Objective
Create a custom Docker network and test communication
between containers.

## Technologies
- Ubuntu Linux
- Docker
- Nginx
- curl

## 1. List Docker Networks
docker network ls

## 2. Create Custom Network
docker network create app-network

## 3. Run Nginx Container
docker run -d --name nginx-network-test \
  --network app-network -p 8082:80 nginx:stable

## 4. Inspect Network
docker network inspect app-network

## 5. Test Container Communication
docker run --rm --network app-network \
  curlimages/curl:latest -I http://nginx-network-test

## Expected Result
The curl container receives an HTTP response from Nginx.

## Learning Outcome
Learned custom bridge networks, container DNS
and container-to-container communication.
