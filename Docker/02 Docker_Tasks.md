# Docker Tasks

## Task 1: Understanding Docker Architecture Components

### Objective

Verify Docker architecture components and workflow.

### Requirements

- Verify Docker Client functionality
- Verify Docker Host functionality
- Verify Docker Daemon responsibilities
- Verify Docker Registry purpose
- Understand Docker workflow from image to container
- Confirm Docker architecture understanding

---

## Task 2: Creating Docker Hub Account

### Objective

Create a Docker Hub account for image storage and sharing.

### Requirements

- Open Docker Hub website
- Click Sign Up
- Enter Docker ID
- Enter email address
- Configure password
- Complete account registration
- Verify email confirmation
- Login to Docker Hub successfully

---

## Task 3: Cloning Java Web Application Project

### Objective

Prepare a sample Java web application for Docker build.

### Requirements

- Clone the sample Maven web application from GitHub
- Navigate to project directory
- Display available project files
- Verify pom.xml file
- Verify src directory
- Confirm project structure readiness

---

## Task 4: Building WAR File Using Maven

### Objective

Generate deployable WAR file before Docker image creation.

### Requirements

- Verify Java installation
- Verify Maven installation
- Execute Maven clean package command
- Verify build execution status
- Check whether target directory is created
- Verify generated WAR file inside target directory
- If target directory is not available, troubleshoot build issue and rebuild
- Confirm successful WAR file generation

---

## Task 5: Creating Dockerfile for Java Web Application

### Objective

Create Dockerfile for containerizing the Java web application.

### Requirements

- Create Dockerfile in project directory
- Add base Tomcat image configuration
- Add WAR file copy instruction
- Save Dockerfile
- Verify Dockerfile content
- Confirm Dockerfile readiness for image build

---

## Task 6: Building Docker Image

### Objective

Build Docker image from Dockerfile.

### Requirements

- Verify Dockerfile availability
- Execute Docker build command
- Add repository name and image tag
- Verify image build process
- Confirm successful Docker image creation
- Display available Docker images

---

## Task 7: Tagging and Pushing Docker Image to Docker Hub

### Objective

Version and upload Docker image to Docker Hub.

### Requirements

- Login to Docker Hub from command line
- Verify Docker Hub authentication
- Tag Docker image with version number
- Push latest image to Docker Hub
- Push versioned image to Docker Hub
- Verify image upload success in Docker Hub repository

---

## Task 8: Running Docker Container from Image

### Objective

Run application container from Docker image.

### Requirements

- Execute Docker run command
- Configure container name
- Configure port mapping
- Run container in detached mode
- Verify running container status
- Access application in browser
- Confirm successful application deployment

---

## Task 9: Managing Docker Containers and Images

### Objective

Verify container and image management operations.

### Requirements

- Display running containers
- Display all containers
- Access running container terminal
- Stop running container
- Remove stopped container
- Remove Docker image
- Verify container removal
- Verify image removal

---

## Task 10: Deploying Docker Image on Separate Deployment Server

### Objective

Verify real-world Docker deployment workflow using deployment server.

### Requirements

- Launch a new deployment server
- Install Docker on deployment server
- Login to Docker Hub
- Pull Docker image from Docker Hub
- Run container using pulled image
- Configure port mapping
- Verify running container status
- Access deployed application in browser
- Confirm successful deployment workflow

---