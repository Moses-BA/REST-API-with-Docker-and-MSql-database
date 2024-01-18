# Docker and MySql database
This repository contains two distinct applications:

- **Grade Submission Spring Boot Application:** A Spring Boot application for grade submission functionality.
- **Docker Compose Configuration:** A configuration for running the application in Docker containers.

## Directory Structure

- **springboot-app:** Contains the source code and build files for the Spring Boot application.
- **docker:** Contains the `docker-compose.yml` file for container orchestration.

## Running the Applications Separately

### 1. Building and Running the Spring Boot Application Independently

**Prerequisites:**

- Java (version compatible with the Spring Boot application)
- Maven or Gradle (depending on the build system used)

**Steps:**

1. Navigate to the `springboot-app` directory:
   ```bash
   cd springboot-apphis repository contains two distinct applications:

- **Grade Submission Spring Boot Application:** A Spring Boot application for grade submission functionality.
- **Docker Compose Configuration:** A configuration for running the application in Docker containers.

## Directory Structure

- **springboot-app:** Contains the source code and build files for the Spring Boot application.
- **docker:** Contains the `docker-compose.yml` file for container orchestration.

## Running the Applications Separately

### 1. Building and Running the Spring Boot Application Independently

**Prerequisites:**

- Java (version compatible with the Spring Boot application)
- Maven or Gradle (depending on the build system used)

**Steps:**

1. Navigate to the `springboot-app` directory:
   ```bash
   cd springboot-app
2. Build the application:
   mvn clean install  # For Maven 
3.Run the application:
   mvn spring-boot:run

# Using Docker Compose to Build and Run the Application in Containers
**Prerequisites:**
Docker
Docker Compose

**Steps:**
1. Navigate to the root directory of the repository:
    ```bash
    cd ..
2. Build and start the containers:
    ```bash
     docker-compose up -d
3. Access the application (typically at http://localhost:8080 or the port specified in docker-compose.yml).

# Additional Notes
If you make changes to the Spring Boot application code, rebuild and restart it accordingly.
For managing containers, use docker-compose commands (e.g., docker-compose down to stop and remove containers).
Refer to the official Docker Compose documentation for more advanced usage: https://docs.docker.com/compose/




