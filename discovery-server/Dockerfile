# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the built jar file from the host to the container
COPY target/discovery-server-1.0-SNAPSHOT.jar /app/discovery-server.jar

# Expose the port that the application will run on
EXPOSE 8761

# Command to run the application
ENTRYPOINT ["java", "-jar", "/app/discovery-server.jar"]
