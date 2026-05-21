# Docker Tasks

## Task 31: Creating Your First Dockerfile

### Objective

Create a basic Dockerfile for building a Docker image.

### Requirements

- Navigate to project directory
- Create a new file named Dockerfile
- Open Dockerfile using text editor
- Add FROM ubuntu:latest instruction
- Add RUN apt update instruction in shell form
- Save Dockerfile changes
- Display Dockerfile content using cat Dockerfile
- Build Docker image
- Verify successful Docker image creation

---

## Task 32: Working with FROM, LABEL, COPY, and ADD Instructions

### Objective

Configure base image, metadata, and file copy instructions inside Dockerfile.

### Requirements

- Open Dockerfile using text editor
- Add FROM tomcat:9-jdk17 instruction
- Add LABEL author="niranjan" instruction
- Add COPY target/*.war /usr/local/tomcat/webapps/ instruction
- Add ADD sample.tar.gz /app/ instruction
- Save Dockerfile changes
- Display Dockerfile content using cat Dockerfile
- Build Docker image
- Verify Docker image build success

---

## Task 33: Working with RUN Instruction

### Objective

Execute commands during Docker image build process using both RUN forms.

### Requirements

- Open Dockerfile using text editor
- Add RUN apt update && apt install -y git wget instruction in shell form
- Add RUN ["echo","Hello Docker"] instruction in executable form
- Save Dockerfile changes
- Execute Docker build command
- Verify RUN shell form execution during build
- Verify RUN executable form execution during build
- Execute docker images command
- Verify newly created Docker image in output

---

## Task 34: Optimizing RUN Layers

### Objective

Reduce Docker image layers by combining RUN instructions.

### Requirements

- Open Dockerfile using text editor
- Identify multiple RUN instructions
- Combine RUN commands using && operator in shell form
- Save Dockerfile changes
- Execute Docker build command
- Verify reduced Docker image build steps
- Execute docker history command
- Confirm optimized Docker image build process

---

## Task 35: Working with CMD Instruction

### Objective

Verify CMD behavior using both shell form and executable form.

### Requirements

- Open Dockerfile using text editor
- Add CMD echo "Hello Docker" instruction in shell form
- Save Dockerfile changes
- Build Docker image
- Run container and verify CMD shell form output
- Open Dockerfile again
- Replace with CMD ["echo","Hello Docker"] instruction in executable form
- Save Dockerfile changes
- Rebuild Docker image
- Run container and verify CMD executable form output
- Run container with runtime command
- Verify CMD override behavior

---

## Task 36: Working with ENTRYPOINT Instruction

### Objective

Verify ENTRYPOINT behavior using both shell form and executable form.

### Requirements

- Open Dockerfile using text editor
- Add ENTRYPOINT ping google.com instruction in shell form
- Save Dockerfile changes
- Build Docker image
- Run container and verify ENTRYPOINT shell form output
- Open Dockerfile again
- Replace with ENTRYPOINT ["ping","google.com"] instruction in executable form
- Save Dockerfile changes
- Rebuild Docker image
- Run container and verify ENTRYPOINT executable form output
- Run container with runtime arguments
- Verify ENTRYPOINT argument passing behavior

---

## Task 37: Combining CMD and ENTRYPOINT

### Objective

Understand how CMD and ENTRYPOINT work together.

### Requirements

- Open Dockerfile using text editor
- Add ENTRYPOINT ["echo","kkfunda"] instruction in executable form
- Add CMD ["how are you"] instruction in executable form
- Save Dockerfile changes
- Execute Docker build command
- Run container without runtime arguments
- Verify combined command execution
- Run container with runtime arguments
- Verify CMD override behavior
- Confirm CMD and ENTRYPOINT integration

---

## Task 38: Using ARG and ENV Variables

### Objective

Configure build-time and runtime variables inside Dockerfile.

### Requirements

- Open Dockerfile using text editor
- Add ARG app_version=1.0 instruction
- Add ENV app_env=production instruction
- Save Dockerfile changes
- Execute Docker build command with build argument
- Verify ARG variable during image build process
- Run container
- Execute env command inside running container
- Verify app_env variable in output
- Confirm successful ARG and ENV variable configuration

---

## Task 39: Working with WORKDIR, USER, and EXPOSE

### Objective

Configure working directory, container user, and exposed ports.

### Requirements

- Open Dockerfile using text editor
- Add WORKDIR /app instruction
- Add USER nobody instruction
- Add EXPOSE 8080 instruction
- Save Dockerfile changes
- Execute Docker build command
- Run container with port mapping
- Execute pwd command inside container
- Verify /app working directory
- Execute docker ps command
- Verify exposed port mapping in output
- Confirm Dockerfile runtime configuration

---

## Task 40: Verifying Docker Image Layers and Build Cache

### Objective

Inspect Docker image layers and verify Docker build cache behavior.

### Requirements

- Execute Docker build command for first image build
- Verify Docker image build steps in terminal output
- Execute docker history command
- Verify Docker image layer details
- Execute Docker build command again without changes
- Verify cached build behavior in output
- Modify one instruction inside Dockerfile
- Save Dockerfile changes
- Execute Docker build command again
- Verify cache invalidation after Dockerfile modification
- Confirm Docker layer and build cache behavior

---
