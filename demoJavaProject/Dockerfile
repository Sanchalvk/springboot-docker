FROM openjdk:17-jdk-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container
COPY build/libs/demo-java-project.jar /app/demo-java-project.jar

# Expose the port that the Spring Boot application runs on (default: 8080)
EXPOSE 8080

# Command to run the Spring Boot application
CMD ["java", "-jar", "demo-java-project.jar"]