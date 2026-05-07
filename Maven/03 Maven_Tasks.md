# Maven  Tasks

---

## Task 22: Cloning Maven Project on EC2 Server

### Objective

Clone the Maven project from GitHub into an EC2 server.

### Requirements

- Connect to the EC2 server  
- Verify Git installation  
- Clone the Maven project from GitHub  
- Navigate to the project directory  
- Display all available project files in the repository  
- Verify src directory and pom.xml file  

---

## Task 23: Building WAR File Using Maven

### Objective

Build a deployable WAR file using Maven.

### Requirements

- Navigate to the Maven project directory  
- Execute the Maven package command  
- Verify source code compilation  
- Verify packaging process  
- Navigate to target directory  
- Verify the generated WAR file inside the target directory  
- Verify generated classes folder  

---

## Task 24: Running Multiple Maven Builds

### Objective

Verify repeated build behavior in Maven.

### Requirements

- Execute Maven package command for first build  
- Observe dependency download logs  
- Verify the generated WAR file inside the target directory  
- Execute Maven package command again  
- Verify faster build execution  
- Confirm dependencies are reused from local repository  

---

## Task 25: Skipping Unit Test Execution

### Objective

Build project without executing unit test cases.

### Requirements

- Execute Maven package command using -DskipTests  
- Verify build success  
- Verify the generated WAR file inside the target directory  
- Confirm test execution is skipped  

---

## Task 26: Skipping Test Compilation Completely

### Objective

Build project by skipping both test execution and test compilation.

### Requirements

- Execute Maven package command using -Dmaven.test.skip=true  
- Verify successful build execution  
- Verify the generated WAR file inside the target directory  
- Confirm test compilation is skipped  

---

## Task 27: Cleaning Build Files

### Objective

Remove previously generated build files.

### Requirements

- Verify target directory contents  
- Execute Maven clean command  
- Verify target directory deletion  
- Confirm old build files are removed  

---

## Task 28: Installing Artifact to Local Repository

### Objective

Store generated artifacts in local Maven repository.

### Requirements

- Execute Maven clean install command  
- Verify successful build execution  
- Navigate to .m2/repository  
- Locate the installed project artifact in the local repository  
- Verify stored WAR file  

---

## Task 29: Verifying Local Repository Storage

### Objective

Inspect Maven local repository artifact structure.

### Requirements

- Navigate to local repository path  
- Locate project package folder  
- Verify version folder structure  
- Verify the stored artifact files in the version directory  
- Confirm successful artifact storage in the local repository  

---

## Task 30: Deploying Artifact to Remote Repository

### Objective

Deploy Maven artifacts to remote repository.

### Requirements

- Configure remote repository details  
- Execute Maven deploy command  
- Verify deployment process  
- Verify artifact upload completion  
- Confirm version-based storage  

---

## Task 31: Verifying Full Maven Deployment Workflow

### Objective

Perform complete Maven build and deployment workflow.

### Requirements

- Clone project on EC2  
- Build WAR file  
- Skip tests when required  
- Clean old files  
- Install artifact locally  
- Deploy artifact remotely  
- Verify final deployment workflow completion  

---
