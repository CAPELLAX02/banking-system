FROM openjdk:17-jdk-slim
COPY target/config-server-0.0.1-SNAPSHOT.jar app.jar
COPY src/main/resources/configurations /configurations
ENTRYPOINT ["java", "-jar", "/app.jar"]