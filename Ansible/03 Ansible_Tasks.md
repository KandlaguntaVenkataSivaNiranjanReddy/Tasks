# Ansible Copy, Template, Variables, Debug & Handlers Practical Lab

## Task 47: Create a Static HTML File

### Objective

Create a static HTML file to deploy on the managed nodes.

### Requirements

- Create a file named index.html.
- Add sample HTML content.
- Save the file.
- Verify the file content.

---

## Task 48: Create a Playbook Using the Copy Module

### Objective

Create an Ansible Playbook to install Apache HTTP Server and copy the HTML file to the managed nodes.

### Requirements

- Create a file named copy.yaml.
- Configure the target hosts.
- Enable privilege escalation.
- Add a task to install the Apache HTTP Server.
- Add a task to start and enable the Apache service.
- Use the Copy module to copy the index.html file.
- Configure the destination path as /var/www/html/index.html.
- Save the Playbook.

---

## Task 49: Execute the Copy Module Playbook

### Objective

Deploy the HTML file using the Copy module.

### Requirements

- Verify the Playbook syntax.
- Execute the Playbook.
- Verify the Playbook execution completed successfully.
- Verify the Apache service is running.

---

## Task 50: Verify the Copy Module Deployment

### Objective

Verify that the HTML file was copied successfully.

### Requirements

- Verify the index.html file exists on the managed nodes.
- Verify the file content.
- Open the web application in a browser.
- Verify the HTML page is displayed successfully.

---

## Task 51: Create a Playbook Using the Template Module

### Objective

Create an Ansible Playbook using the Template module.

### Requirements

- Modify the existing index.html file.
- Replace the static content with dynamic variables.
- Use the variables location and date inside the HTML file.
- Create a file named template.yaml.
- Configure the target hosts.
- Enable privilege escalation.
- Define Playbook variables.
- Install the Apache HTTP Server.
- Start and enable the Apache service.
- Use the Template module to deploy the HTML file.
- Save the Playbook.

---

## Task 52: Execute the Template Module Playbook

### Objective

Deploy the HTML file using the Template module.

### Requirements

- Verify the Playbook syntax.
- Execute the Playbook.
- Verify the Playbook execution completed successfully.
- Verify the Template module deployed the HTML file successfully.

---

## Task 53: Verify the Template Module Deployment

### Objective

Verify that the Template module replaced the variables successfully.

### Requirements

- Verify the deployed HTML file.
- Open the web application in a browser.
- Verify the variable values are displayed correctly.
- Compare the output with the Copy module deployment.

---

## Task 54: Create an External Variables File

### Objective

Create an external variables file to store reusable variables.

### Requirements

- Create a file named vars.yaml.
- Define the required variables.
- Save the file.
- Verify the file content.

---

## Task 55: Configure vars_files in the Playbook

### Objective

Load variables from an external YAML file.

### Requirements

- Open the existing template.yaml Playbook.
- Configure vars_files.
- Include the vars.yaml file.
- Save the Playbook.

---

## Task 56: Execute the Playbook Using vars_files

### Objective

Deploy the application using variables from an external file.

### Requirements

- Verify the Playbook syntax.
- Execute the Playbook.
- Verify the Playbook execution completed successfully.
- Open the web application.
- Verify the values are loaded from the external variables file.

---

## Task 57: Execute the Playbook Using Runtime Variables

### Objective

Override variable values during Playbook execution.

### Requirements

- Execute the Playbook using runtime variables (-e).
- Pass custom values while executing the Playbook.
- Verify the Playbook execution completed successfully.
- Open the web application.
- Verify the runtime variable values are displayed.

---

## Task 58: Verify Variable Precedence

### Objective

Understand the priority of variables in Ansible.

### Requirements

- Define the same variable in the Playbook.
- Define the same variable in the external variables file.
- Execute the Playbook.
- Verify which value is displayed.
- Execute the Playbook again using runtime variables.
- Verify the variable precedence.

---

## Task 59: Create a Playbook Using the Debug Module

### Objective

Display variable values during Playbook execution.

### Requirements

- Create a file named debug.yaml.
- Define sample variables.
- Use the Debug module to print variable values.
- Save the Playbook.

---

## Task 60: Execute the Debug Playbook

### Objective

Verify the Debug module output.

### Requirements

- Verify the Playbook syntax.
- Execute the Playbook.
- Verify the Debug module displays the variable values successfully.

---

## Task 61: Create a Playbook Using Handlers

### Objective

Restart the Apache service only when changes occur.

### Requirements

- Create a file named handler.yaml.
- Configure the target hosts.
- Enable privilege escalation.
- Install the Apache HTTP Server.
- Start and enable the Apache service.
- Use the Template module to deploy the HTML file.
- Configure a notify statement.
- Create a Handler to restart the Apache service.
- Save the Playbook.

---

## Task 62: Execute the Handler Playbook

### Objective

Verify the execution of Handlers.

### Requirements

- Verify the Playbook syntax.
- Execute the Playbook.
- Verify the Handler is triggered when changes occur.
- Execute the Playbook again without making changes.
- Verify the Handler is not triggered.

---

## Task 63: Compare Tasks and Handlers

### Objective

Understand the difference between Tasks and Handlers.

### Requirements

- Observe the execution of normal tasks.
- Observe the execution of Handlers.
- Identify when Handlers are triggered.
- Compare the execution behavior of both.

---

## Task 64: Perform End-to-End Validation

### Objective

Validate all the concepts covered in this practical lab.

### Requirements

- Verify the Copy module deployment.
- Verify the Template module deployment.
- Verify Playbook variables.
- Verify external variables (vars_files).
- Verify runtime variables (-e).
- Verify variable precedence.
- Verify the Debug module.
- Verify Handlers.
- Confirm the successful completion of the practical lab.