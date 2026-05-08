# SonarQube Tasks

---

## Task 1: Verifying SonarQube Server Status

### Objective

Verify whether SonarQube server is running properly.

### Requirements

- Switch to sonar user  
- Navigate to SonarQube bin directory  
- Check SonarQube service status  
- Verify whether SonarQube is running  
- Identify startup issues if service is not running  

---

## Task 2: Practicing SonarQube Startup Using Root User
### Objective

Understand what happens when SonarQube is started using the root user.

### Requirements

Switch to root user
Navigate to SonarQube bin directory
Attempt to start the SonarQube service using root user
Check SonarQube service status
Observe the startup behavior
Verify why SonarQube should not run using root user 

---

## Task 3: Practicing SonarQube Startup Using Sonar User
### Objective

Start SonarQube using the recommended user account.

### Requirements

Switch to sonar user
Navigate to SonarQube bin directory
Start the SonarQube service using startup script
Check SonarQube service status
Verify successful SonarQube startup
Compare the difference from root user startup behavior  

---

## Task 4: Checking SonarQube Logs

### Objective

Identify startup failure root cause.

### Requirements

- Navigate to SonarQube logs directory  
- Open SonarQube log file for inspection  
- Verify Elasticsearch error logs  
- Identify startup failure reason  

---

## Task 5: Fixing Temp Directory Issue

### Objective

Resolve SonarQube startup failure.

### Requirements

- Navigate to SonarQube temp directory  
- Verify temporary files  
- Remove temporary files from the temp directory  
- Restart SonarQube server  
- Verify successful startup status  

---

## Task 6: Accessing SonarQube Dashboard

### Objective

Verify SonarQube dashboard accessibility.

### Requirements

- Open a web browser  
- Access SonarQube dashboard URL  
- Login to SonarQube dashboard  
- Verify successful dashboard access  

---

## Task 7: Exploring SonarQube Dashboard

### Objective

Understand major sections in SonarQube dashboard.

### Requirements

- Open Projects section  
- Open Issues section  
- Open Quality Profiles section  
- Open Quality Gates section  
- Open Administration section  
- Verify successful dashboard navigation  

---

## Task 8: Updating pom.xml for Sonar Integration

### Objective

Integrate Maven project with SonarQube.

### Requirements

- Connect to Maven server  
- Navigate to Maven project directory  
- Open pom.xml file  
- Add Sonar host URL  
- Add SonarQube authentication credentials  
- Save configuration changes  

---

## Task 9: Running First Sonar Scan

### Objective

Generate first SonarQube report.

### Requirements

- Navigate to Maven project directory  
- Execute the mvn sonar:sonar command  
- Verify scan execution logs  
- Verify report upload to SonarQube server  

---

## Task 10: Verifying SonarQube Project Report

### Objective

View generated project analysis report.

### Requirements

- Login to SonarQube dashboard  
- Open Projects section  
- Open scanned project  
- Verify the bugs report in project analysis  
- Verify the vulnerabilities report in project analysis  
- Verify the code smells report in project analysis  
- Verify the duplication report in project analysis  
- Verify the code coverage report in project analysis  

---

