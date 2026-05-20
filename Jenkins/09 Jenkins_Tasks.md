# Jenkins Tasks

## Task 81: Creating a Jenkins Agent Node
### Objective

Create a new Jenkins agent node for distributed build execution.

### Requirements

- Launch a new EC2 Linux instance for agent node  
- Verify SSH access to the agent server  
- Create a working directory for Jenkins agent  
- Login to Jenkins dashboard  
- Navigate to Manage Jenkins → Manage Nodes  
- Click New Node  
- Enter agent node name  
- Select Permanent Agent  
- Create the agent node  

## Task 82: Configuring Jenkins Agent Node Settings
### Objective

Configure basic settings for Jenkins agent node.

### Requirements

- Open agent node configuration  
- Configure number of executors  
- Configure remote root directory  
- Add node label  
- Select node usage option  
- Save configuration changes  
- Verify agent configuration details  

## Task 83: Configuring SSH Connection for Agent Node
### Objective

Connect Jenkins master with agent node using SSH.

### Requirements

- Open agent node configuration  
- Select Launch agents via SSH option  
- Add agent server IP address  
- Add SSH credentials  
- Configure SSH username  
- Add private key content  
- Configure host key verification strategy  
- Save configuration changes  
- Verify SSH connection configuration  

## Task 84: Installing Required Packages on Agent Node
### Objective

Prepare Jenkins agent node for remote build execution.

### Requirements

- Connect to agent server using SSH  
- Verify whether Java is installed  
- Install Java package if not available  
- Verify Java installation  
- Verify whether Git is installed  
- Install Git package if not available  
- Verify Git installation  
- Confirm agent server readiness  

## Task 85: Verifying Agent Node Connection
### Objective

Verify successful Jenkins master and agent communication.

### Requirements

- Open Jenkins dashboard  
- Navigate to Build Executor Status  
- Verify current node status  
- Open node logs if node is offline  
- Verify connection errors if available  
- Restart node connection if required  
- Verify node online status  

## Task 86: Restricting Freestyle Jobs to Agent Node
### Objective

Run Jenkins jobs only on specific agent nodes.

### Requirements

- Open Jenkins freestyle job configuration  
- Enable Restrict where this project can be run option  
- Add node label in label expression field  
- Save job configuration  
- Trigger build manually  
- Verify build execution on agent node  

## Task 87: Verifying Executor and Build Queue Behavior
### Objective

Verify job execution behavior based on executor count.

### Requirements

- Verify current executor count on agent node  
- Trigger multiple Jenkins jobs simultaneously  
- Verify first job execution on agent node  
- Verify queued jobs in build queue  
- Increase executor count in node configuration  
- Trigger multiple jobs again  
- Verify parallel job execution after executor increase  

## Task 88: Adding Multiple Agent Nodes with Same Label
### Objective

Distribute Jenkins jobs across multiple agent nodes.

### Requirements

- Launch a second EC2 Linux instance  
- Install Java and Git on second agent node  
- Create Jenkins Node2 configuration  
- Assign same label as Node1  
- Save node configuration  
- Verify both nodes are online  
- Trigger multiple Jenkins jobs  
- Verify automatic job distribution across nodes  

## Task 89: Running Pipeline Jobs Using Node Labels
### Objective

Run Jenkins pipeline jobs on labeled agent nodes.

### Requirements

- Open Jenkins pipeline job configuration  
- Replace agent any with label-based configuration  
- Add node label in pipeline script  
- Save pipeline configuration  
- Trigger pipeline build  
- Verify pipeline execution on labeled agent node  

## Task 90: Verifying Distributed Build Execution
### Objective

Verify how Jenkins distributes builds across master and agents.

### Requirements

- Trigger same Jenkins job multiple times  
- Verify job execution across available agent nodes  
- Verify queued jobs when executors are busy  
- Verify automatic build pickup after executor becomes free  
- Verify source code checkout on agent node  
- Verify job configuration storage on master node  
- Confirm successful distributed build execution  
