# Jenkins  Tasks

---

## Task 1: Creating Your First Jenkins Freestyle Job

### Objective

Create a basic Jenkins freestyle project for CI/CD automation.

### Requirements

- Login to Jenkins dashboard  
- Click on New Item  
- Enter project name  
- Select Freestyle Project  
- Create the job  
- Add project description  
- Save job configuration  

---

## Task 2: Installing Git on Jenkins Server

### Objective

Prepare Jenkins server for Git integration.

### Requirements

- Connect to Jenkins server  
- Verify whether Git is already installed  
- Install Git package if not available  
- Verify Git installation  
- Return to Jenkins dashboard  

---

## Task 3: Configuring GitHub Source Code Integration

### Objective

Connect Jenkins job with GitHub source code.

### Requirements

- Open Jenkins job configuration  
- Navigate to Source Code Management section  
- Select Git option  
- Add GitHub repository URL  
- Add GitHub credentials  
- Select development branch  
- Save configuration changes  

---

## Task 4: Configuring Maven in Jenkins

### Objective

Configure Maven globally in Jenkins.

### Requirements

- Navigate to Manage Jenkins  
- Open Global Tool Configuration  
- Add Maven installation  
- Provide Maven name  
- Select Maven version  
- Save Maven configuration  

---

## Task 5: Configuring Maven Build Step

### Objective

Build application artifacts using Jenkins.

### Requirements

- Open Jenkins job configuration  
- Navigate to Build section  
- Add build step  
- Select Invoke top-level Maven targets  
- Add Maven goal as clean package  
- Save configuration changes  

---

# SonarQube Integration Flow

---

## Task 6: Updating pom.xml for SonarQube Integration

### Objective

Integrate SonarQube scanning in Jenkins build.

### Requirements

- Open GitHub repository  
- Switch to development branch  
- Open pom.xml file  
- Add SonarQube properties  
- Save configuration changes  
- Push updated code to GitHub  

---

## Task 7: Configuring SonarQube Build in Jenkins

### Objective

Run code quality analysis from Jenkins.

### Requirements

- Open Jenkins job configuration  
- Edit Maven build goals  
- Update goal to clean package sonar:sonar  
- Save configuration changes  
- Trigger Jenkins build  
- Verify SonarQube project creation  

---

# Nexus Integration Flow

---

## Task 8: Configuring Nexus Deployment in Jenkins

### Objective

Deploy build artifacts to Nexus repository.

### Requirements

- Connect to Jenkins server  
- Locate Maven settings.xml file  
- Open settings.xml file  
- Add Nexus credentials  
- Save configuration changes  
- Open pom.xml file  
- Add distributionManagement configuration  
- Push updated code to GitHub  

---

## Task 9: Deploying Artifacts to Nexus from Jenkins

### Objective

Automate artifact deployment to Nexus.

### Requirements

- Open Jenkins job configuration  
- Update Maven goal to clean package sonar:sonar deploy  
- Save configuration changes  
- Trigger Jenkins build  
- Verify artifact deployment in Nexus repository  

---

# Tomcat Deployment Flow

---

## Task 10: Deploying WAR File to Tomcat Using Jenkins

### Objective

Automate application deployment to Tomcat.

### Requirements

- Install Deploy to Container plugin  
- Open Jenkins job configuration  
- Add post-build action  
- Select Deploy war/ear to container  
- Provide WAR file path  
- Configure Tomcat URL  
- Add Tomcat credentials  
- Verify manager-script role in Tomcat  
- Trigger Build Now  
- Verify full CI/CD pipeline execution  

---
