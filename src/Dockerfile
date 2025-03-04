# Use the official Amazon Corretto 21 image
FROM amazoncorretto:21

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container's /app directory
COPY out/artifacts/HelloDocker_jar/HelloDocker.jar /app/testdocker.jar

# Expose port 8080 (or the port your application uses)
EXPOSE 8080

# Run the application using java
CMD ["java", "-jar", "/app/testdocker.jar"]
