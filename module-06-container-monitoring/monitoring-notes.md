# Container Monitoring Notes

## Container 1
Name: monitoring-nginx
Port: 8083

## Container 2
Name: nginx-limited
Port: 8084
Memory Limit: 128 MiB
CPU Limit: 0.5 CPU

## Monitoring Commands
- docker stats
- docker logs
- docker top
- docker inspect

## Results
Record observed CPU usage, memory usage, container state,
and HTTP response status.
