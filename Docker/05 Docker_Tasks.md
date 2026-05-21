# Docker Networking Tasks

## Task 1: Understanding Docker Network Basics

### Objective

Verify Docker networking components and default network availability.

### Requirements

- Verify Docker service is running
- Display available Docker networks
- Identify default Docker networks
- Verify bridge network
- Verify host network
- Verify none network
- Confirm Docker network readiness

---

## Task 2: Running Containers in Default Bridge Network

### Objective

Launch containers in Docker’s default bridge network.

### Requirements

- Verify available Docker images
- Run first container without specifying network
- Verify container creation
- Run second container without specifying network
- Verify second container creation
- Display running containers
- Confirm both containers are connected to default bridge network

---

## Task 3: Inspecting Container Network Details

### Objective

Verify Docker network assignment and container IP addresses.

### Requirements

- Inspect first container
- Verify connected Docker network
- Verify assigned container IP address
- Inspect second container
- Verify connected Docker network
- Verify assigned container IP address
- Confirm successful IP assignment for both containers

---

## Task 4: Testing Container Service Connectivity Using IP Address

### Objective

Verify application-level communication between containers using IP address and service port.

### Requirements

- Verify first container IP address
- Verify second container IP address
- Verify application port running in second container
- Enter first container terminal
- Execute curl command using second container IP address and service port
- Verify successful service response
- Exit first container terminal
- Enter second container terminal
- Execute curl command using first container IP address and service port
- Verify successful service response
- Confirm successful service-level communication between containers

---

## Task 5: Testing Container Communication Using Ping

### Objective

Verify network-level communication between containers using ICMP.

### Requirements

- Enter first container terminal
- Install ping utility if not available
- Ping second container using IP address
- Verify successful ping response
- Exit first container
- Enter second container terminal
- Ping first container using IP address
- Verify successful ping response
- Confirm network-level communication success

---

## Task 6: Creating Custom Bridge Network

### Objective

Create a user-defined bridge network for name-based communication.

### Requirements

- Create custom bridge network
- Verify custom network creation
- Display available Docker networks
- Run third container in custom bridge network
- Verify container creation
- Run fourth container in custom bridge network
- Verify container creation
- Confirm containers are attached to custom network

---

## Task 7: Testing Name-Based Communication in Custom Bridge Network

### Objective

Verify Docker internal DNS and name-based communication.

### Requirements

- Enter third container terminal
- Ping fourth container using container name
- Verify successful ping response
- Ping fourth container using IP address
- Verify successful ping response
- Exit third container
- Confirm Docker internal DNS communication success

---

## Task 8: Connecting Container to Multiple Networks

### Objective

Connect a running container to an additional Docker network.

### Requirements

- Verify current container network details
- Connect first container to custom bridge network
- Inspect first container
- Verify multiple network attachments
- Verify default bridge network connection
- Verify custom bridge network connection
- Test communication with containers in custom network
- Confirm successful multi-network communication

---

## Task 9: Managing Docker Networks

### Objective

Create, inspect, and remove Docker networks.

### Requirements

- Create a new Docker network
- Verify network creation
- Display all Docker networks
- Inspect the created network
- Remove unused Docker networks using prune
- Verify remaining Docker networks
- Confirm Docker network cleanup success

---

## Task 10: Working with Host and None Networks

### Objective

Verify container behavior in host and none network modes.

### Requirements

- Run container using host network mode
- Verify container shares host network
- Verify container has no separate IP address
- Stop host network container
- Run container using none network mode
- Inspect none network container
- Verify isolated network configuration
- Confirm host and none network behavior