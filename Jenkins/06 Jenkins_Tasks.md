# Jenkins  Tasks

---

## Task 51: Creating Jenkins Declarative Pipeline Job

### Objective

Create a Jenkins pipeline job for declarative pipeline execution.

### Requirements

- Login to Jenkins dashboard  
- Click on New Item  
- Enter pipeline job name  
- Select Pipeline project type  
- Create the pipeline job  
- Verify pipeline job creation  
- Install Pipeline Stage View plugin if stage view is not visible  

---

## Task 52: Writing Basic Declarative Pipeline Structure

### Objective

Create a basic declarative pipeline structure.

### Requirements

- Open pipeline job configuration  
- Navigate to pipeline script section  
- Create pipeline block  
- Configure agent any block  
- Create sample stages block  
- Create sample steps block  
- Save pipeline configuration  
- Trigger build  
- Verify successful basic pipeline execution  

---

## Task 53: Configuring Git Checkout Stage

### Objective

Pull source code from GitHub repository inside declarative pipeline.

### Requirements

- Open Jenkins pipeline configuration  
- Navigate to Pipeline Syntax generator  
- Select Git option  
- Provide repository URL  
- Provide branch name  
- Add Git credentials  
- Generate Git checkout script  
- Add checkout stage in pipeline script  
- Trigger build  
- Verify successful code checkout  

---

## Task 54: Configuring Maven Tool in Declarative Pipeline

### Objective

Use Jenkins configured Maven tool inside declarative pipeline.

### Requirements

- Navigate to Global Tool Configuration  
- Verify Maven installation  
- Open pipeline script  
- Configure tools block  
- Add Maven tool name  
- Save pipeline configuration  
- Verify Maven configuration  

---

## Task 55: Building Application Using Maven

### Objective

Build application artifact inside declarative pipeline.

### Requirements

- Add build stage in pipeline script  
- Execute Maven clean package command  
- Save pipeline configuration  
- Trigger build  
- Verify successful build execution  
- Verify WAR file generation inside target directory  

---

# SonarQube Integration Flow

---

## Task 56: Running SonarQube Analysis

### Objective

Generate code quality reports from declarative pipeline.

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

## Task 57: Deploying Artifact to Nexus

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

## Task 58: Deploying WAR File to Tomcat

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

# Post Build Flow

---

## Task 59: Configuring Post Block

### Objective

Execute actions after pipeline completion.

### Requirements

- Open pipeline script  
- Add post block  
- Configure success condition  
- Configure failure condition  
- Add notification method inside post block  
- Save pipeline configuration  
- Trigger build  
- Verify post block execution  

---

# Slack Notification Flow

---

## Task 60: Configuring Slack Notifications in Declarative Pipeline

### Objective

Send build notifications to Slack from declarative pipeline.

### Requirements

- Verify Slack plugin configuration  
- Create notifyBuild function  
- Configure STARTED notification  
- Configure SUCCESS notification  
- Configure FAILURE notification  
- Configure color-based notification logic  
- Add slackSend command  
- Trigger pipeline build  
- Verify Slack notification delivery  

---
