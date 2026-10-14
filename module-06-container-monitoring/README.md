# Module 6: Docker Container Monitoring & Resource Management

## Objective
Monitor Docker containers, inspect logs, and configure resource limits.

## Tools
- Docker
- Nginx
- Ubuntu Linux

## 1. Monitor Resource Usage
docker stats monitoring-nginx

## 2. View Container Logs
docker logs monitoring-nginx

## 3. Inspect Processes
docker top monitoring-nginx

## 4. Inspect Container State
docker inspect -f '{{.State.Status}}' monitoring-nginx

## 5. Configure Resource Limits
docker run -d --name nginx-limited \
  --memory 128m --cpus 0.5 -p 8084:80 nginx:stable

## 6. Test HTTP Response
curl -I http://localhost:8083

## Learning Outcomes
- Container CPU and memory monitoring
- Log inspection
- Process monitoring
- Resource constraints
- Basic HTTP health verification
