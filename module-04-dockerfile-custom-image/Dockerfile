FROM eclipse-temurin:21-jre

WORKDIR /app

COPY module-03-java-maven-build/target/deployment-monitoring-app-1.0.0.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
