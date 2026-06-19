# Ansible Playbook Practical Lab Tasks

## Task 29: Executing Multiple Tasks Using Ansible Ad-Hoc Commands

### Objective
Understand how to perform multiple administrative tasks using Ansible Ad-Hoc commands.

### Requirements

- Create a file named `index.html`
- Add sample HTML content to `index.html`
- Save the `index.html` file
- Install Apache HTTP Server using Ansible Ad-Hoc command
- Copy `index.html` file to Managed Nodes
- Start Apache HTTP service
- Verify successful execution of all commands
- Observe the need to execute multiple commands individually
- Confirm the limitations of Ad-Hoc command execution

---

## Task 30: Creating the First Ansible Playbook

### Objective
Create an Ansible Playbook to automate Apache HTTP Server deployment.

### Requirements

- Create a file named `httpd.yaml`
- Configure target hosts
- Configure become privileges
- Add task to install Apache HTTP Server
- Add task to copy the existing `index.html` file
- Add task to start Apache HTTP service
- Save the Playbook
- Verify Playbook YAML content

---

## Task 31: Verifying Playbook Syntax

### Objective
Validate the Playbook before execution.

### Requirements

- Execute Playbook syntax check
- Verify successful syntax validation
- Identify YAML syntax errors if present
- Fix syntax errors if required
- Confirm Playbook readiness

---

## Task 32: Executing the Ansible Playbook

### Objective
Deploy Apache HTTP Server using the Ansible Playbook.

### Requirements

- Execute `httpd.yaml` Playbook
- Verify Playbook execution
- Verify Apache package installation
- Verify `index.html` file copied successfully
- Verify Apache service startup
- Confirm successful Playbook execution

---

## Task 33: Verifying Apache Deployment

### Objective
Validate successful Apache deployment.

### Requirements

- Verify Apache package installation
- Verify Apache service status
- Verify `index.html` file under `/var/www/html`
- Access Apache application in browser (if applicable)
- Confirm successful Apache deployment

---

## Task 34: Creating Git Installation Playbook

### Objective
Create a Playbook to automate Git installation.

### Requirements

- Create a file named `git.yaml`
- Configure target hosts
- Configure become privileges
- Add Git installation task
- Save the Playbook
- Verify Playbook YAML content

---

## Task 35: Verifying and Executing Git Installation Playbook

### Objective
Install Git on all Managed Nodes using an Ansible Playbook.

### Requirements

- Execute Playbook syntax check
- Execute `git.yaml` Playbook
- Verify successful Playbook execution
- Verify Git installation using `git --version`
- Confirm successful Git installation

---

## Task 36: Creating Unzip Installation Playbook

### Objective
Create a Playbook to automate Unzip installation.

### Requirements

- Create a file named `unzip.yaml`
- Configure target hosts
- Configure become privileges
- Add Unzip installation task
- Save the Playbook
- Verify Playbook YAML content

---

## Task 37: Verifying and Executing Unzip Installation Playbook

### Objective
Install Unzip on all Managed Nodes using an Ansible Playbook.

### Requirements

- Execute Playbook syntax check
- Execute `unzip.yaml` Playbook
- Verify successful Playbook execution
- Verify Unzip installation
- Confirm successful Unzip installation

---

## Task 38: Creating a Playbook Using the File Module

### Objective
Create a file on Managed Nodes using the Ansible File module.

### Requirements

- Create a file named `file.yaml`
- Configure target hosts
- Configure become privileges
- Add File module task
- Configure file path as `/tmp/ansible-demo.txt`
- Configure file owner
- Configure file group
- Configure file permissions
- Configure file state as `touch`
- Save the Playbook
- Verify Playbook YAML content

---

## Task 39: Verifying and Executing File Module Playbook

### Objective
Create a file on Managed Nodes using the Ansible File module.

### Requirements

- Execute Playbook syntax check
- Execute `file.yaml` Playbook
- Verify successful Playbook execution
- Verify file creation
- Confirm successful File module execution

---

## Task 40: Verifying File Creation on Managed Nodes

### Objective
Validate file creation on all Managed Nodes.

### Requirements

- Display `/tmp` directory contents
- Verify `ansible-demo.txt` file creation
- Verify file ownership
- Verify file group
- Verify file permissions
- Confirm successful file creation

---

## Task 41: Exploring File Module States

### Objective
Understand different states supported by the Ansible File module.

### Requirements

- Review `touch` state
- Review `file` state
- Review `directory` state
- Review `link` state
- Review `hard` state
- Review `absent` state
- Understand the purpose of each state

---

## Task 42: Configuring the Ansible Control Node in Inventory

### Objective
Configure the Ansible Control Node in the inventory file.

### Requirements

- Open `/etc/ansible/hosts`
- Add Control Node entry
- Configure SSH username
- Configure PEM file path
- Save inventory configuration
- Verify inventory entries
- Confirm Control Node configuration

---

## Task 43: Verifying Inventory Configuration

### Objective
Validate the inventory configuration.

### Requirements

- Display inventory configuration
- Verify Control Node entry
- Verify Managed Node entries
- Verify inventory order
- Confirm successful inventory configuration

---

## Task 44: Verifying Connectivity Using Ansible Ping Module

### Objective
Verify connectivity to all inventory hosts.

### Requirements

- Execute `ansible all -m ping`
- Verify successful SSH authentication
- Verify pong response from all hosts
- Identify unreachable hosts if any
- Confirm successful Ansible connectivity

---

## Task 45: Understanding Inventory Organization

### Objective
Understand proper inventory organization in Ansible.

### Requirements

- Review Control Node placement
- Review standalone host entries
- Review inventory group ordering
- Understand inventory parsing behavior
- Confirm inventory organization understanding

---

## Task 46: Final Validation of Ansible Playbooks

### Objective
Verify successful Playbook creation, execution, and inventory configuration.

### Requirements

- Verify Ad-Hoc command execution
- Verify Playbook creation
- Verify Playbook syntax validation
- Verify Apache deployment
- Verify Git installation
- Verify Unzip installation
- Verify File module execution
- Verify inventory configuration
- Verify Ansible connectivity
- Confirm successful Ansible Playbook implementation
