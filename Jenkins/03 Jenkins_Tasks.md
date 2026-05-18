# Jenkins Tasks

---

## Task 21: Updating Jenkins Public IP Configuration

### Objective

Fix Jenkins access issues after server restart.

### Requirements

- Connect to Jenkins server  
- Navigate to Jenkins configuration directory  
- Open jenkins.model.JenkinsLocationConfiguration.xml file  
- Verify old public IP configuration  
- Update new public IP address  
- Save configuration changes  
- Restart Jenkins  
- Verify Jenkins dashboard accessibility  

---

## Task 22: Disabling Jenkins Job During Maintenance

### Objective

Prevent new builds during maintenance activities.

### Requirements

- Login to Jenkins dashboard  
- Open an existing Jenkins job  
- Disable the Jenkins job  
- Verify disabled job status  
- Attempt triggering build  
- Verify build restriction behavior  
- Enable the job again  
- Verify job availability  

---

# Maven Project Flow

---

## Task 23: Installing Maven Integration Plugin

### Objective

Configure Jenkins Maven project support.

### Requirements

- Navigate to Manage Jenkins  
- Open Manage Plugins section  
- Search for Maven Integration Plugin  
- Install the plugin  
- Verify plugin installation  

---

## Task 24: Creating Jenkins Maven Project

### Objective

Build Maven applications using Jenkins Maven project type.

### Requirements

- Click New Item  
- Enter project name  
- Select Maven Project  
- Configure Root POM path  
- Select Maven version  
- Add build goals as clean package  
- Save configuration  
- Trigger build  
- Verify successful build execution  

---

## Task 25: Performing Normal Restart

### Objective

Restart Jenkins immediately.

### Requirements

- Trigger normal restart using restart URL  
- Verify Jenkins shutdown behavior  
- Verify interruption of running builds  
- Verify Jenkins restart completion  

---

## Task 26: Performing Safe Restart

### Objective

Restart Jenkins safely without interrupting running builds.

### Requirements

- Install Safe Restart plugin  
- Trigger safe restart  
- Verify running builds completion  
- Verify Jenkins restart completion  

---

## Task 27: Changing Jenkins Build Number

### Objective

Manage custom build numbering.

### Requirements

- Install Next Build Number plugin  
- Open Jenkins job  
- Navigate to Set Next Build Number  
- Enter custom build number  
- Save configuration  
- Trigger build  
- Verify updated build number  

---

## Task 28: Configuring Audit Trail Plugin

### Objective

Track Jenkins administrative activities.

### Requirements

- Install Audit Trail plugin  
- Navigate to Configure System  
- Enable audit logging  
- Configure audit log file path  
- Configure log retention settings  
- Save configuration  
- Trigger job changes  
- Verify audit logs  

---

## Task 29: Restoring Deleted Job Using Config History

### Objective

Recover accidentally deleted Jenkins jobs.

### Requirements

- Install Job Config History plugin  
- Delete a sample Jenkins job  
- Open Job Config History section  
- Locate deleted job record  
- Restore deleted job  
- Verify successful job recovery  

---

## Task 30: Managing Build Parameters and Views

### Objective

Improve Jenkins job flexibility and dashboard organization.

### Requirements

- Configure Build With Parameters option  
- Create choice parameters for branch selection  
- Trigger parameterized build  
- Verify dynamic branch selection  
- Create a new Jenkins view  
- Add jobs to the view  
- Verify dashboard organization  

---
