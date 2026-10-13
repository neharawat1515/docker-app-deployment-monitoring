# Module 4: Dockerfile & Custom Image Creation

## Objective
Package a Java application into a custom Docker image.

## Technologies
- Ubuntu Linux
- Java 21
- Maven
- Docker
- Eclipse Temurin JRE

## Dockerfile Instructions
- FROM: Selects the base image.
- WORKDIR: Sets the container working directory.
- COPY: Copies the application JAR.
- ENTRYPOINT: Executes the Java application.

## Image Build
docker build -t deployment-monitoring-app:v1 -f module-04-dockerfile-custom-image/Dockerfile .

## Image Verification
docker images

## Container Execution
docker run --name deployment-app-v1 deployment-monitoring-app:v1

## Expected Result
The Java application runs inside a Docker container and prints its status messages.
