# Docker Tasks

## Task 1: Building Spring Boot Application Docker Image

### Objective

Prepare the application image for Docker persistence practice.

### Requirements

- Clone the Spring Boot MongoDB Docker project from GitHub
- Navigate to project directory
- Verify project files
- Verify Dockerfile availability
- Execute Docker build command
- Verify successful Docker image creation
- Display available Docker images
- Confirm application image readiness

---

## Task 2: Creating Custom Docker Network

### Objective

Create a Docker network for application and database communication.

### Requirements

- Create a custom Docker network
- Display available Docker networks
- Verify newly created network
- Confirm Docker network readiness for container communication

---

## Task 3: Running Spring Boot Application Without MongoDB

### Objective

Verify application dependency failure when database container is missing.

### Requirements

- Run Spring Boot application container
- Configure application environment variables
- Verify container startup
- Access application in browser
- - Attempt user registration through application UI 
- Verify application database connection failure
- Confirm MongoDB dependency requirement

---

## Task 4: Running MongoDB Without Data Persistence

### Objective

Verify MongoDB container behavior without volume or bind mount.

### Requirements

- Run MongoDB container without any volume mapping
- Verify MongoDB container startup
- Verify Spring Boot application connectivity
- Access application in browser
- Register sample users
- Confirm successful data storage in MongoDB
- Verify MongoDB database records
- Confirm data is stored only inside container filesystem

---

## Task 5: Simulating MongoDB Container Crash and Verifying Data Loss

### Objective

Understand why container data is lost without persistence.

### Requirements

- Verify stored user records in MongoDB
- Stop and remove MongoDB container forcefully
- Recreate MongoDB container without persistence
- Verify MongoDB startup
- Check database records again
- Verify missing user data
- Confirm container data loss behavior

---

## Task 6: Configuring Bind Mount for Data Persistence

### Objective

Persist MongoDB data using host system bind mount.

### Requirements

- Create backup folder in host system
- Verify host system backup folder path
- Remove old MongoDB container if running
- Run MongoDB container with bind mount mapping
- Verify bind mount configuration
- Verify MongoDB container startup
- Confirm bind mount persistence setup

---

## Task 7: Verifying Bind Mount Data Persistence

### Objective

Verify data recovery after container recreation using bind mount.

### Requirements

- Access application in browser
- Register sample users again
- Verify MongoDB records
- Force remove MongoDB container
- Recreate MongoDB container using same bind mount path
- Verify MongoDB startup
- Check database records again
- Confirm successful data persistence using bind mount

---

## Task 8: Configuring Docker Volume for Data Persistence

### Objective

Persist MongoDB data using Docker-managed volume.

### Requirements

- Create Docker volume
- Display available Docker volumes
- Remove existing MongoDB container
- Run MongoDB container using Docker volume
- Verify volume mapping configuration
- Verify MongoDB startup
- Confirm Docker volume persistence setup

---

## Task 9: Verifying Docker Volume Data Persistence

### Objective

Verify Docker-managed volume behavior after container crash.

### Requirements

- Access application in browser
- Register sample users
- Verify MongoDB records
- Force remove MongoDB container
- Recreate MongoDB container using same Docker volume
- Verify MongoDB startup
- Check database records again
- Confirm successful data persistence using Docker volume

---

## Task 10: Inspecting Docker Volume Storage and Comparing Persistence Methods

### Objective

Verify Docker volume storage location and compare bind mount vs volume behavior.

### Requirements

- Display available Docker volumes
- Verify Docker volume details
- Navigate to Docker volume storage path
- Verify stored volume data
- Compare bind mount storage location
- Compare Docker volume storage location
- Verify bind mount characteristics
- Verify Docker volume characteristics
- Confirm Docker persistence method understanding
