# Docker Volume Notes

- Docker volumes store persistent data outside a container's writable layer.
- A volume can be mounted into multiple containers.
- Removing a container does not automatically remove its named volume.
- `docker volume ls` lists volumes.
- `docker volume create app-data` creates a volume.
- `docker volume inspect app-data` displays volume details.
- `tar -czf` creates a compressed backup archive.
- `tar -xzf` extracts a compressed backup archive.

## Practical Verification
Test data was saved in app-data and verified after removing the original container.
The backup was restored into app-data-restored.
