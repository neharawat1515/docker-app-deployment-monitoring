# Image Build Notes

## Image Name
deployment-monitoring-app:v1

## Base Image
eclipse-temurin:21-jre

## Application Artifact
module-03-java-maven-build/target/deployment-monitoring-app-1.0.0.jar

## Build Command
docker build -t deployment-monitoring-app:v1 -f module-04-dockerfile-custom-image/Dockerfile .

## Verification
docker images

## Container Test
docker run --name deployment-app-v1 deployment-monitoring-app:v1

## Result
Record the actual image build result and application output.
