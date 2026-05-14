
# Nexus Tasks

## Task 11: Verifying Snapshot Artifact in Nexus

### Objective

Verify uploaded snapshot artifact.

### Requirements

- Login to Nexus dashboard  
- Open snapshot repository  
- Verify uploaded WAR artifact in snapshot repository  
- Verify timestamp-based version generation  
- Verify artifact folder structure  

---

## Task 12: Deploying Snapshot Build Again

### Objective

Understand multiple snapshot deployments.

### Requirements

- Execute mvn clean deploy command again  
- Verify successful deployment  
- Open snapshot repository  
- Verify creation of a new timestamp version  

---

## Release Deployment Flow

---

## Task 13: Updating Project Version to Release

### Objective

Prepare project for release deployment.

### Requirements

- Open pom.xml file  
- Remove the SNAPSHOT keyword from project version  
- Save configuration changes  
- Verify release version format  

---

## Task 14: Deploying Artifact to Release Repository

### Objective

Deploy stable artifact to release repository.

### Requirements

- Execute mvn clean deploy command  
- Verify deployment success  
- Verify successful release artifact upload  

---

## Task 15: Verifying Release Artifact in Nexus

### Objective

Verify uploaded release artifact.

### Requirements

- Login to Nexus dashboard  
- Open release repository  
- Verify uploaded WAR file  
- Verify version-based artifact storage structure  

---

## Task 16: Attempting Duplicate Release Deployment

### Objective

Understand release redeployment restrictions.

### Requirements

- Execute mvn clean deploy command again  
- Observe release deployment failure  
- Verify duplicate deployment error  
- Identify redeployment restriction behavior  

---

## Task 17: Changing Version for New Release Deployment

### Objective

Deploy a new release version properly.

### Requirements

- Open pom.xml file  
- Update the project release version  
- Save configuration changes  
- Execute mvn clean deploy command  
- Verify successful deployment  

---

## Task 18: Verifying Multiple Release Versions

### Objective

Verify version-based artifact storage.

### Requirements

- Open release repository  
- Verify old version artifact  
- Verify new version artifact  
- Compare different version folders  
- Confirm version tracking behavior  

---

## Redeployment Flow

---

## Task 19: Enabling Release Redeployment

### Objective

Allow redeployment for the same release version.

### Requirements

- Navigate to release repository settings  
- Open hosted configuration  
- Enable the redeploy option for release artifacts  
- Save configuration changes  
- Verify updated settings  

---

## Task 20: Redeploying Same Release Version

### Objective

Redeploy existing release artifact version.

### Requirements

- Navigate to Maven project directory  
- Execute mvn clean deploy command  
- Verify successful redeployment  
- Verify release artifact overwrite behavior  

---
