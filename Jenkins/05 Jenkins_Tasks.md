# Jenkins Tasks

---

## Task 41: Creating Jenkins Pipeline Job

### Objective

Create a Jenkins pipeline job for scripted pipeline execution.

### Requirements

- Login to Jenkins dashboard  
- Click on New Item  
- Enter pipeline job name  
- Select Pipeline project type  
- Create the pipeline job  
- Verify pipeline job creation  
- Install Pipeline Stage View plugin if stage view is not visible  

---

## Task 42: Writing Basic Scripted Pipeline Structure

### Objective

Create a basic scripted pipeline using Groovy syntax.

### Requirements

- Open pipeline job configuration  
- Navigate to pipeline script section  
- Write node block structure  
- Create sample stage block  
- Save pipeline configuration  
- Trigger build  
- Verify basic pipeline execution  

---

## Task 43: Configuring Git Checkout Stage

### Objective

Pull source code from GitHub repository inside pipeline.

### Requirements

- Open Jenkins pipeline configuration  
- Navigate to Pipeline Syntax generator  
- Select Git option  
- Provide repository URL  
- Provide branch name  
- Add Git credentials  
- Generate Git checkout script  
- Add Git checkout stage in pipeline script  
- Trigger build  
- Verify successful code checkout  

---

## Task 44: Configuring Maven Tool in Scripted Pipeline

### Objective

Use Jenkins configured Maven tool inside pipeline script.

### Requirements

- Navigate to Global Tool Configuration  
- Verify Maven installation  
- Open pipeline script  
- Define Maven tool variable using tool command  
- Save pipeline configuration  
- Verify Maven path configuration  

---

## Task 45: Building Application Using Maven

### Objective

Build application artifact inside scripted pipeline.

### Requirements

- Add build stage in pipeline script  
- Execute Maven clean package command  
- Save pipeline configuration  
- Trigger pipeline build  
- Verify successful build execution  
- Verify WAR file generation inside target directory  

---

# SonarQube Integration Flow

---

## Task 46: Running SonarQube Analysis

### Objective

Generate code quality reports from pipeline.

### Requirements

- Verify SonarQube configuration in pom.xml  
- Add SonarQube stage in pipeline script  
- Execute Maven sonar command  
- Save pipeline configuration  
- Trigger build  
- Verify SonarQube analysis report generation  

---

# Nexus Integration Flow

---

## Task 47: Deploying Artifact to Nexus

### Objective

Upload build artifact to Nexus repository.

### Requirements

- Verify Nexus credentials in settings.xml  
- Verify distributionManagement configuration in pom.xml  
- Add Nexus deployment stage in pipeline script  
- Execute Maven deploy command  
- Trigger build  
- Verify successful artifact upload in Nexus repository  

---

# Tomcat Deployment Flow

---

## Task 48: Deploying WAR File to Tomcat

### Objective

Deploy application to Tomcat using curl command.

### Requirements

- Verify Tomcat manager credentials  
- Add deployment stage in pipeline script  
- Configure curl deployment command  
- Verify WAR file path  
- Trigger build  
- Verify successful deployment in Tomcat  
- Verify application accessibility in browser  

---

# Error Handling Flow

---

## Task 49: Implementing try-catch-finally Block

### Objective

Handle pipeline failures properly.

### Requirements

- Open pipeline script  
- Add try block for pipeline stages  
- Add catch block for failure handling  
- Configure build failure status  
- Re-throw exceptions  
- Save pipeline configuration  
- Verify failure handling behavior  

---

# Slack Notification Flow

---

## Task 50: Configuring Slack Notifications in Scripted Pipeline

### Objective

Send build notifications to Slack from pipeline.

### Requirements

- Verify Slack plugin configuration  
- Create notifyBuild function  
- Configure STARTED notification  
- Configure SUCCESS notification  
- Configure FAILURE notification  
- Add color configuration for notifications  
- Add slackSend command  
- Trigger pipeline build  
- Verify Slack notification delivery  

---
