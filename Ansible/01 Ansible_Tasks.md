# Ansible Practical Lab Tasks

## Task 1: Launching Ansible Lab Environment

### Requirements

- Launch 3 Red Hat Linux EC2 instances
- Verify all instances are running
- Connect to all instances using SSH
- Configure hostnames for all servers
- Verify hostname configuration
- Confirm Ansible lab environment readiness 

---  

## Task 2: Installing Ansible on Control Node 

### Requirements

- Connect to Ansible Control Node
- Verify Python installation
- Install Ansible package
- Verify successful installation
- Check Ansible version
- Confirm Ansible installation readiness

---

## Task 3: Configuring Static Inventory

### Requirements

- Open /etc/ansible/hosts
- Add Managed Node private IP addresses
- Configure SSH username
- Configure PEM file name
- Save inventory configuration
- Verify inventory entries
- Confirm inventory configuration readiness

---

## Task 4: Copying PEM File Content

### Requirements

- Open PEM file on local machine
- Display PEM file content
- Copy complete PEM file content
- Verify PEM file content availability
- Confirm PEM file content readiness

---

## Task 5: Creating PEM File on Ansible Control Node

### Requirements

- Create PEM file on Control Node 
- Open PEM file using vi editor 
- Paste copied PEM content
- Save PEM file
- Verify PEM file creation
- Confirm PEM file readiness

---

## Task 6: Configuring PEM File Permissions

### Requirements

- Configure PEM file permissions
- Verify updated permissions
- Confirm PEM file accessibility
- Confirm SSH authentication readiness

---

## Task 7: Verifying Connectivity Using Ansible Ping Module

### Requirements

- Execute ansible all -m ping
- Verify successful host connectivity
- Verify pong response from Managed Nodes
- Identify unreachable hosts if any
- Confirm successful Ansible communication

---

## Task 8: Exploring Ansible Modules

### Requirements

- Execute ansible-doc -l
- Display available Ansible modules
- Search for ping module
- Search for yum module
- Search for copy module
- Verify module information
- Confirm module exploration

---

## Task 9: Executing Ad-Hoc Commands Using Shell Module

### Objective

Execute shell commands on Managed Nodes using Ansible.

### Requirements

- Execute disk usage command on all hosts
- Verify disk space information
- Execute date command on all hosts
- Verify current date and time output
- Execute uptime command on all hosts
- Verify server uptime information
- Confirm successful shell command execution

---

## Task 10: Executing Commands Without Explicit Shell Module

### Objective

Verify default shell module behavior in Ansible.

### Requirements

- Execute date command without specifying shell module
- Execute uptime command without specifying shell module
- Create abc.txt file on all hosts
- Change file permissions on abc.txt
- Verify successful command execution
- Confirm default shell module behavior

---

## Task 11: Verifying File Creation on Managed Nodes

### Objective

Verify files created through Ansible commands.

### Requirements

- Login to Managed Nodes
- Display available files
- Verify abc.txt file creation
- Verify file ownership
- Verify file permissions
- Confirm successful file creation

---

## Task 12: Creating Host Groups in Inventory

### Objective

Organize servers into logical groups.

### Requirements

- Open /etc/ansible/hosts file
- Create db group
- Create app group
- Assign Managed Nodes to groups
- Save inventory configuration
- Verify host group entries
- Confirm successful inventory grouping

---

## Task 13: Executing Commands on Specific Host Groups

### Objective

Run commands only on selected server groups.

### Requirements

- Execute command on db group
- Verify command execution on db servers
- Verify command is not executed on app servers
- Execute command on app group
- Verify command execution on app servers
- Confirm successful group-based execution

---

## Task 14: Installing Git Package on DB Servers

### Objective

Install software packages on specific host groups.

### Requirements

- Execute Git installation command on db group
- Verify package installation failure due to insufficient privileges
- Execute package installation using become option
- Verify successful Git installation
- Verify Git package availability
- Confirm successful package installation

---

## Task 15: Verifying Git Installation on DB Servers

### Objective

Verify package installation on selected hosts.

### Requirements

- Execute Git version command on db group
- Verify Git version output
- Login to DB server
- Verify Git installation locally
- Confirm successful Git installation verification

---

## Task 16: Verifying Package Availability Across Groups

### Objective

Compare package installation between server groups.

### Requirements

- Verify Git installation on db servers
- Verify Git is unavailable on app servers
- Compare command output between groups
- Confirm group-specific package deployment

---

## Task 17: Changing File Permissions on DB Servers

### Objective

Manage file permissions on selected host groups.

### Requirements

- Modify abc.txt permissions on db group
- Verify permission change execution
- Display file details on db server
- Verify updated file permissions
- Confirm successful permission modification

---

## Task 18: Verifying File Permissions Across Groups

### Objective

Compare file permissions between server groups.

### Requirements

- Display abc.txt file details on all hosts
- Verify updated permissions on db servers
- Verify original permissions on app servers
- Compare permission differences
- Confirm group-specific file management

---

## Task 19: Installing Java on All Servers

### Objective

Install Java package across all Managed Nodes.

### Requirements

- Execute Java installation command on all hosts
- Verify package installation
- Verify Java package availability
- Execute Java version command
- Verify Java installation output
- Confirm successful Java installation

---

## Task 20: Installing Apache HTTP Server

### Objective

Install Apache web server on all Managed Nodes.

### Requirements

- Execute httpd package installation command
- Verify successful package installation
- Verify httpd package availability
- Confirm successful Apache installation

---

## Task 21: Verifying Apache Service Status

### Objective

Verify Apache service state after installation.

### Requirements

- Check httpd service status on all hosts
- Verify service is inactive
- Verify service is disabled
- Confirm initial Apache service state

---

## Task 22: Starting Apache Service Using Service Module

### Objective

Start Apache service using Ansible service module.

### Requirements

- Execute service start command
- Verify successful service start operation
- Verify service state change
- Confirm Apache service startup

---

## Task 23: Verifying Running Apache Service

### Objective

Validate Apache service availability.

### Requirements

- Check httpd service status
- Verify service is active
- Verify service is running
- Confirm successful Apache service operation

---

## Task 24: Managing Package States Using Yum Module

### Objective

Understand package lifecycle management.

### Requirements

- Install package using state=present
- Update package using state=latest
- Remove package using state=absent
- Verify package state changes
- Confirm package lifecycle management understanding

---

## Task 25: Restarting Apache Service

### Objective

Manage Apache service restart operations.

### Requirements

- Execute Apache service restart command
- Verify restart operation
- Verify service remains active
- Confirm successful service restart

---

## Task 26: Stopping Apache Service

### Objective

Stop Apache service using Ansible.

### Requirements

- Execute Apache service stop command
- Verify service stop operation
- Verify service state is stopped
- Confirm successful service shutdown

---

## Task 27: Verifying Apache Service After Stop Operation

### Objective

Validate Apache service status after stopping.

### Requirements

- Check Apache service status
- Verify service is inactive
- Verify service is stopped
- Confirm successful service status verification

---

## Task 28: Final Validation of Ansible Fundamentals and Ad-Hoc Commands

### Objective

Verify understanding of Ansible fundamentals and ad-hoc command execution.

### Requirements

- Verify inventory configuration
- Verify SSH authentication
- Verify Ansible ping operation
- Verify module exploration
- Verify shell command execution
- Verify host group management
- Verify package management
- Verify file permission management
- Verify service management
- Confirm successful Ansible fundamentals understanding

---