# Troubleshooting

## Container not running
Check:
docker ps -a

## Port already allocated
Choose an unused host port.

## No logs visible
Generate an HTTP request and check logs again.

## Container health check fails
Verify that the configured health-check command
exists inside the image.

## Resource limits not visible
Inspect the container configuration:
docker inspect nginx-limited
