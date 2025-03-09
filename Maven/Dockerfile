# Use maven:3.6.3-jdk-11 as a parent image
FROM maven:3.6.3-jdk-11

# Set the working directory
WORKDIR /app

# Copy the pom.xml file and the source code
COPY pom.xml .
COPY src ./src

# Package the application
RUN mvn clean package

# Run the application
CMD ["java", "-jar", "target/your-app.jar"]