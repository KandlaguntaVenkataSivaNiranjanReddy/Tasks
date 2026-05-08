# Apache Tomcat Tasks

---

## Task 1: Installing Java for Tomcat

### Objective

Install Java as a prerequisite for Tomcat setup.

### Requirements

- Launch an EC2 Linux server  
- Connect to the server using SSH  
- Switch to root user  
- Navigate to /opt directory  
- Install Java JDK package  
- Verify Java installation using version command  

---

## Task 2: Installing Required Utilities

### Objective

Install required tools needed for Tomcat installation.

### Requirements

- Verify the currently installed system packages  
- Install wget utility package  
- Install unzip utility package  
- Verify whether both utilities are installed successfully  

---

## Task 3: Downloading Tomcat Package

### Objective

Download Apache Tomcat package from the official website.

### Requirements

- Open Apache Tomcat official download page  
- Copy Tomcat download URL  
- Navigate to /opt directory  
- Download Tomcat package using wget  
- Verify whether the package is downloaded successfully  

---

## Task 4: Extracting Tomcat Package

### Objective

Extract the downloaded Tomcat package.

### Requirements

- Verify the downloaded Tomcat compressed file  
- Extract the Tomcat package  
- Verify the extracted Tomcat directory  
- Display all extracted files and directories  
- Navigate into the Tomcat directory  

---

## Task 5: Exploring Tomcat Directory Structure

### Objective

Inspect important Tomcat directories.

### Requirements

- Navigate to the Tomcat installation directory  
- Verify the bin directory  
- Verify the conf directory  
- Verify the lib directory  
- Verify the logs directory  
- Verify the webapps directory  
- Verify the work directory  
- Verify the temp directory  

---

## Task 6: Starting Tomcat Server

### Objective

Start the Tomcat server using startup scripts.

### Requirements

- Navigate to the Tomcat bin directory  
- Verify available shell scripts  
- Provide execute permission to required scripts  
- Start Tomcat using startup.sh  
- Start Tomcat using catalina.sh  
- Verify Tomcat startup logs for successful startup  

---

## Task 7: Accessing Tomcat from Browser

### Objective

Access Tomcat server from a browser using EC2 public IP.

### Requirements

- Verify Tomcat running status  
- Open EC2 security group settings  
- Add inbound rule for port 8080  
- Save security group changes  
- Access Tomcat homepage using public IP address  
- Verify successful loading of Tomcat homepage  

---

## Task 8: Configuring Manager App Access

### Objective

Enable remote access for Tomcat Manager App.

### Requirements

- Navigate to Manager application directory  
- Open context.xml file  
- Remove IP restriction configuration  
- Save configuration changes  
- Navigate to tomcat-users.xml file  
- Create manager user credentials  
- Restart Tomcat server  
- Verify Manager App login access  

---

## Task 9: Configuring Host Manager Access

### Objective

Enable remote access for Tomcat Host Manager.

### Requirements

- Navigate to Host Manager directory  
- Open context.xml file  
- Remove IP restriction configuration  
- Save configuration changes  
- Restart Tomcat server  
- Login to Host Manager  
- Verify successful access  

---

## Task 10: Managing Tomcat from Anywhere Using Symbolic Links

### Objective

Start and stop Tomcat from any location using shortcut commands.

### Requirements

- Create symbolic link for Tomcat startup script  
- Create symbolic link for Tomcat shutdown script  
- Verify symbolic link creation  
- Start Tomcat using custom command  
- Stop Tomcat using custom command  
- Verify Tomcat service status  

---
