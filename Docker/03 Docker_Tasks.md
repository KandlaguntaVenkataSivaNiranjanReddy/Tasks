# Docker Tasks

## Task 21: Managing Multiple Docker Containers

### Objective

Create and run multiple containers from the same Docker image.

### Requirements

- Verify Docker image availability
- Run first container with a unique container name
- Configure host and container port mapping
- Run second container using the same image
- Configure a different host port for second container
- Verify both containers are running successfully
- Confirm multiple container deployment from the same image

---

## Task 22: Creating Container Without Running Immediately

### Objective

Create a container and start it manually later.

### Requirements

- Run Docker container without detached mode
- Verify container created state
- Display container status
- Start the container manually using Docker start
- Verify running container status
- Confirm successful manual container startup

---

## Task 23: Renaming and Accessing Containers

### Objective

Manage container naming and access container terminal.

### Requirements

- Verify existing running container
- Rename container using Docker rename command
- Verify updated container name
- Access container terminal using Docker exec
- Navigate inside container file system
- Exit from container terminal
- Confirm successful container access

---

## Task 24: Inspecting Container Details

### Objective

View detailed container configuration and metadata.

### Requirements

- Verify running container availability
- Execute Docker inspect command
- Verify container ID and name
- Verify image information
- Verify port mapping details
- Verify network information
- Confirm successful container inspection

---

## Task 25: Managing Container States

### Objective

Control container execution states using Docker commands.

### Requirements

- Stop a running container gracefully
- Verify stopped container status
- Start container again
- Pause running container
- Verify paused container state
- Unpause container
- Kill running container forcefully
- Verify exited container state

---

## Task 26: Viewing Logs and Running Processes

### Objective

Monitor container activity and running processes.

### Requirements

- Verify running container availability
- Display container logs
- Stream live logs using follow option
- View running processes inside container
- Verify application process status
- Confirm successful log and process monitoring

---

## Task 27: Monitoring Container Resource Usage

### Objective

Monitor live container resource consumption.

### Requirements

- Verify running containers
- Execute Docker stats command
- Verify CPU usage details
- Verify memory usage details
- Verify network usage details
- Confirm successful resource monitoring

---

## Task 28: Applying Memory Limits and Verifying Container Behavior

### Objective

Control container memory usage and verify OOM behavior.

### Requirements

- Run container with memory limit configuration
- Verify running container status
- Monitor memory usage using Docker stats
- Check container status after execution
- Verify container exit behavior if memory exceeds limit
- Inspect container for OOMKilled status
- Confirm memory limit behavior

---

## Task 29: Copying Files Between Host and Container

### Objective

Transfer files between host machine and Docker container.

### Requirements

- Copy file from host to running container
- Verify file transfer inside container
- Copy file from container to host
- Verify file availability on host machine
- Confirm successful file transfer in both directions

---

## Task 30: Managing Dangling Images and Creating New Image from Container

### Objective

Manage unused Docker images and create a new image from container changes.

### Requirements

- Verify available Docker images
- Identify dangling images
- Check dangling image usage status
- Stop and remove container if image is in use
- Execute Docker image prune command
- Modify a running container
- Create a new Docker image using Docker commit
- Verify newly created Docker image
- Confirm successful Docker image management

---