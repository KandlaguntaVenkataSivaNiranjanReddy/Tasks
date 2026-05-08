
# SonarQube Tasks

## Task 11: Viewing Sonar Issues

### Objective

Inspect detailed project issues.

### Requirements

- Open project dashboard  
- Navigate to Issues section  
- Filter project issues by bugs  
- Filter project issues by vulnerabilities  
- Filter project issues by code smells  
- Verify issue severity levels  
- Verify estimated fix time  

---

## Task 12: Generating Sonar Authentication Token

### Objective

Generate secure authentication token.

### Requirements

- Navigate to user security settings  
- Open token generation section  
- Create token name  
- Generate a new authentication token  
- Copy generated token securely  

---

## Task 13: Updating pom.xml with Token Authentication

### Objective

Replace hardcoded credentials with secure token authentication.

### Requirements

- Open pom.xml file  
- Remove password configuration  
- Replace login credentials with authentication token  
- Save configuration changes  

---

## Task 14: Running Secure Sonar Scan

### Objective

Run Sonar analysis using token authentication.

### Requirements

- Navigate to Maven project directory  
- Execute mvn clean sonar:sonar command  
- Verify successful authentication  
- Verify successful SonarQube report generation  

---

## Task 15: Changing SonarQube Default Port

### Objective

Modify SonarQube default port configuration.

### Requirements

- Navigate to SonarQube conf directory  
- Open sonar.properties file  
- Locate port configuration  
- Change the default SonarQube port number  
- Save configuration changes  

---

## Task 16: Restarting SonarQube After Port Change

### Objective

Apply new SonarQube port configuration.

### Requirements

- Restart SonarQube server  
- Verify server status  
- Open new port in security group  
- Access SonarQube dashboard using the updated port number  
- Verify successful access  

---

## Task 17: Updating Maven Configuration After Port Change

### Objective

Reconnect Maven project to updated SonarQube port.

### Requirements

- Open pom.xml file  
- Update Sonar host URL port  
- Save configuration changes  
- Execute SonarQube scan command  
- Verify successful connection  

---

## Task 18: Creating Custom Quality Profile

### Objective

Create custom quality rules for project scanning.

### Requirements

- Navigate to Quality Profiles  
- Create new profile  
- Select programming language  
- Create blank profile  
- Verify profile creation  
- Activate required quality rules for the profile  

---

## Task 19: Creating Custom Quality Gate

### Objective

Create project validation conditions.

### Requirements

- Navigate to Quality Gates  
- Create new quality gate  
- Unlock editing  
- Add project validation conditions  
- Save configuration  
- Assign quality gate to project  

---

## Task 20: Managing Users Groups and Permissions

### Objective

Control project access in SonarQube.

### Requirements

- Create SonarQube users  
- Create user groups  
- Configure project permissions  
- Add users to groups  
- Verify group memberships  
- Verify permission assignments  

---