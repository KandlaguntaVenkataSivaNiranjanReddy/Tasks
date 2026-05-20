# Docker Tasks

## Task 1: Launching Ubuntu Server

### Objective

Prepare a Linux server for Docker installation.

### Requirements

- Launch a new Ubuntu EC2 instance
- Verify instance running status
- Connect to the server using SSH
- Verify successful server login
- Update server package lists
- Confirm server readiness for Docker installation

---

## Task 2: Installing Docker

### Objective

Install Docker on the Ubuntu server.

### Requirements

- Verify updated package lists
- Install Docker using Ubuntu apt package manager
- Monitor Docker installation process
- Verify successful Docker installation
- Check installed Docker version

---

## Task 3: Verifying Docker Installation

### Objective

Validate successful Docker installation on the Linux server.

### Requirements

- Execute Docker version command
- Verify installed Docker version
- Execute Docker info command
- Verify Docker daemon information
- Confirm successful Docker installation

---

## Task 4: Verifying Docker Service

### Objective

Verify Docker daemon service status and operations.

### Requirements

- Check Docker service status
- Verify Docker daemon is running
- Restart Docker service if required
- Verify Docker service after restart
- Confirm Docker service availability

---

## Task 5: Fixing Docker Permission Issue

### Objective

Allow non-root users to execute Docker commands without sudo access.

### Requirements

- Execute Docker command without sudo
- Verify permission denied error
- Add current user to Docker group
- Logout from current session
- Login to the server again
- Verify Docker group membership
- Confirm successful Docker permission configuration

---

## Task 6: Running Docker Commands Without sudo

### Objective

Execute Docker commands using normal user access.

### Requirements

- Execute docker ps command
- Execute docker info command
- Execute docker images command
- Verify successful command execution
- Confirm Docker works without sudo access

---

## Task 7: Managing Docker Service Operations

### Objective

Manage Docker daemon service operations in Linux.

### Requirements

- Stop Docker service manually
- Verify Docker service stopped successfully
- Start Docker service manually
- Verify Docker service running status
- Restart Docker service
- Confirm Docker service availability after restart

---

## Task 8: Verifying Docker Service Auto Start After Reboot

### Objective

Ensure Docker service starts automatically after system reboot.

### Requirements

- Verify Docker service enable status
- Enable Docker service if required
- Restart the Linux server
- Login to the server again
- Verify Docker service running status after reboot
- Confirm Docker auto-start configuration

---

## Task 9: Running hello-world Container

### Objective

Verify Docker container execution by running the hello-world sample container.

### Requirements

- Run the Docker hello-world container
- Verify automatic image download from Docker Hub
- Verify successful container creation
- Verify hello-world container execution output
- Confirm successful Docker container execution

---

## Task 10: Final Docker Environment Validation

### Objective

Perform final validation of the complete Docker installation and configuration.

### Requirements

- Verify Docker version
- Verify Docker service status
- Verify Docker group configuration
- Verify Docker commands without sudo
- Verify hello-world container execution
- Confirm successful Docker installation and configuration

---