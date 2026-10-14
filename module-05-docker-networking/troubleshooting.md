# Docker Networking Troubleshooting

## Error: Network already exists
Inspect the existing network using:
docker network inspect app-network

## Error: Container name already in use
Check existing containers:
docker ps -a

## Error: Connection refused
Check whether the Nginx container is running:
docker ps

## Error: Could not resolve host
Confirm that both containers use the same custom network.

## Error: Port already allocated
Choose another unused host port.

## Error: Image pull failed
Check internet connectivity and Docker Hub access.
