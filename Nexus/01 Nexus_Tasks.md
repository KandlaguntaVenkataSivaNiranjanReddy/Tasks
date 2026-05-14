# Nexus Tasks

---

## Task 1: Verifying Nexus Dashboard Access

### Objective

Verify whether Nexus repository manager is accessible.

### Requirements

- Open a web browser  
- Access Nexus dashboard URL  
- Login using admin credentials  
- Verify successful dashboard access  
- Explore the repositories section in Nexus dashboard  

---

## Task 2: Exploring Default Nexus Repositories

### Objective

Understand default repositories available in Nexus.

### Requirements

- Navigate to repositories section  
- Verify hosted repositories  
- Verify proxy repositories  
- Verify group repositories  
- Understand different repository types available in Nexus  

---

## Task 3: Creating Snapshot Repository

### Objective

Create a repository for storing development artifacts.

### Requirements

- Navigate to repository creation section  
- Select maven2 (hosted) repository type  
- Provide snapshot repository name  
- Configure version policy as Snapshot  
- Save repository configuration  
- Verify repository creation  

---

## Task 4: Creating Release Repository

### Objective

Create a repository for storing production artifacts.

### Requirements

- Navigate to repository creation section  
- Select maven2 (hosted) repository type  
- Provide release repository name  
- Configure version policy as Release  
- Save repository configuration  
- Verify repository creation  

---

## Task 5: Verifying Repository URLs

### Objective

Verify repository URLs for Maven integration.

### Requirements

- Open snapshot repository  
- Copy snapshot repository URL  
- Verify copied repository URL  
- Open release repository  
- Copy release repository URL  
- Verify copied repository URL  

---

## Task 6: Updating pom.xml for Nexus Integration

### Objective

Configure Maven project for Nexus deployment.

### Requirements

- Connect to Maven server  
- Navigate to Maven project directory  
- Open pom.xml file  
- Add distributionManagement section in pom.xml  
- Configure release repository URL  
- Configure snapshot repository URL  
- Save configuration changes  

---

## Task 7: Configuring Nexus Credentials

### Objective

Configure secure authentication for Nexus deployment.

### Requirements

- Navigate to Maven settings.xml file  
- Open the servers section in settings.xml  
- Add Nexus server ID  
- Add Nexus username  
- Add Nexus password  
- Save configuration changes  

---

## Task 8: Verifying Maven Configuration

### Objective

Verify Maven Nexus integration setup.

### Requirements

- Open pom.xml file  
- Verify repository configuration  
- Open settings.xml file  
- Verify credentials configuration  
- Confirm Maven Nexus integration readiness  

---

## Snapshot Deployment Flow

---

## Task 9: Verifying Snapshot Version

### Objective

Verify snapshot version before deployment.

### Requirements

- Open pom.xml file  
- Verify project version  
- Confirm project version contains the SNAPSHOT keyword  
- Save configuration if required  

---

## Task 10: Deploying Artifact to Snapshot Repository

### Objective

Deploy development build to snapshot repository.

### Requirements

- Navigate to Maven project directory  
- Execute the mvn clean deploy command  
- Verify build process  
- Verify deployment success  

---
