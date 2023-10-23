FROM openjdk:8

# Set the working directory within the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/reclamationDocker.jar reclamationDocker.jar

# Copy the "resources" directory into the container
COPY src/main/resources/ resources/

# Expose the port your application is listening on (if necessary)
EXPOSE 8089

# Define the entry point
ENTRYPOINT ["java", "-jar", "reclamationDocker.jar"]