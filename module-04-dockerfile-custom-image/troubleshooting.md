# Troubleshooting

## Error: COPY failed
Check the JAR path and confirm that the build context is the project root.

## Error: Dockerfile not found
Verify the path passed to the -f option.

## Error: Maven JAR missing
Build Module 3 again using mvn clean package.

## Error: Image pull failed
Check internet connectivity and Docker Hub access.

## Error: Container name conflict
Inspect the existing container using docker ps -a.
Remove it only if it is no longer needed.
