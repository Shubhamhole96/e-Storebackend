# Use a base image with Java 11 installed
FROM adoptopenjdk:11-jre-hotspot

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file (assuming you've already built the Spring Boot application)
COPY target/your-spring-boot-app.jar app.jar

# Expose the port on which your Spring Boot application listens
EXPOSE 8080

# Start the Java application when the container starts
CMD ["java", "-jar", "app.jar"]
