# Troubleshooting

## Docker permission denied
Use `sudo docker` when the current user does not have permission to access Docker.

## Container is not running
A container exits when its main process finishes. Use a long-running process if you need to execute commands inside it.

## Backup file not found
Check the backup folder and verify the archive path before restoring.

## Restored file not found
Verify the backup archive contents with `tar -tzf` before restoring it.
