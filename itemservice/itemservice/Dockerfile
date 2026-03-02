FROM eclipse-temurin:21-jdk-alpine
WORKDIR /app
COPY target/*.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]

# Base image for the build process. The image used is from the Eclipse Temurin project. Image is alpine
# Sets the current working directory inside the container to /app for all subsequent instructions (like COPY and ENTRYPOINT)
# Docker copies target/*.jar to app.jar
# This defines the command that will be executed when a container starts from this image