# Tomcat Tasks

---

## Task 11: Changing Tomcat Port Number

### Objective

Change the default Tomcat port to avoid application conflicts.

### Requirements

- Navigate to Tomcat conf directory  
- Open server.xml file  
- Locate default port configuration  
- Change Tomcat port from 8080 to 9090  
- Save configuration changes  
- Restart Tomcat server  
- Verify Tomcat access using new port  

---

## Task 12: Verifying Security Group Access

### Objective

Allow browser access to the new Tomcat port.

### Requirements

- Open AWS EC2 security group settings  
- Add inbound rule for new Tomcat port  
- Save security group configuration  
- Access Tomcat using public IP and new port  
- Verify Tomcat homepage loading  

---

## Task 13: Preparing WAR File for Transfer
### Objective

Prepare the generated WAR file for deployment.

### Requirements

- Navigate to the Maven project directory
- Verify whether the target directory exists
- Verify whether the WAR file is already available inside the target directory
- If the WAR file is not available, execute the Maven package command
- Verify successful WAR file generation
- Navigate to the target directory
- Copy WAR file to /tmp directory
- Verify WAR file availability in /tmp directory

---

## Task 14: Downloading WAR File from Maven Server

### Objective

Download the generated WAR file from Maven server.

### Requirements

- Exit from remote server session  
- Use SCP command from local system  
- Download WAR file from remote server  
- Save WAR file in local machine  
- Verify downloaded WAR file  

---

## Task 15: Deploying WAR File Using Tomcat Manager UI

### Objective

Deploy WAR file using Tomcat Manager web interface.

### Requirements

- Login to Tomcat Manager application  
- Navigate to WAR deployment section  
- Choose WAR file from local system  
- Upload WAR file  
- Deploy application  
- Verify application deployment  

---

## Task 16: Verifying Deployed Application

### Objective

Verify deployed application access.

### Requirements

- Open deployed application URL  
- Verify application loading  
- Check deployed application context path  
- Confirm successful deployment  

---

## Task 17: Deploying WAR from Server Path

### Objective

Deploy WAR file directly from server location.

### Requirements

- Copy WAR file to /tmp directory on Tomcat server  
- Verify WAR file location  
- Login to Tomcat Manager  
- Navigate to server path deployment section  
- Provide context path  
- Provide WAR file location  
- Deploy application  
- Verify deployment success  

---

## Task 18: Exploring Tomcat Webapps Directory

### Objective

Verify how Tomcat stores deployed applications.

### Requirements

- Navigate to Tomcat webapps directory  
- Verify uploaded WAR file  
- Verify extracted application folder  
- Confirm deployment structure  

---

## Task 19: Installing Apache HTTP Server

### Objective

Install Apache HTTP server on the Linux server.

### Requirements

- Verify HTTP server status  
- Install Apache HTTPD package  
- Start Apache service  
- Verify Apache service status  
- Open port 80 in security group  
- Access Apache homepage in browser  

---

## Task 20: Hosting Static Website Using Apache

### Objective

Host static web content using Apache HTTP server.

### Requirements

- Navigate to /var/www/html directory  
- Create index.html file  
- Add sample HTML content  
- Save the file  
- Access application in browser  

---
