# Use a base image with Java installed
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/studentserver-0.0.1-SNAPSHOT.jar studentserver-0.0.1-SNAPSHOT.jar

# Expose the port your Spring Boot application runs on
EXPOSE 9192

# Command to run the JAR file
ENTRYPOINT ["java", "-jar", "studentserver-0.0.1-SNAPSHOT.jar"]
