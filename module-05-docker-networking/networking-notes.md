# Docker Networking Notes

## Default Networks
- bridge
- host
- none

## Custom Network
Name: app-network
Driver: bridge

## Test Container
Name: nginx-network-test

## Port Mapping
Host: 8082
Container: 80

## Communication Test
A temporary curl container sends an HTTP request
to the Nginx container using its container name.

## Result
Record the actual HTTP status and network inspection results.
