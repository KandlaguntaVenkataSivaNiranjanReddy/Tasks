# Jenkins Tasks

---

## Task 11: Copying Existing Jenkins Job

### Objective

Create a new Jenkins job by copying an existing job configuration.

### Requirements

- Login to Jenkins dashboard  
- Click New Item  
- Enter new job name  
- Select Copy from existing job option  
- Choose existing Jenkins job  
- Create copied job  
- Verify copied job configuration  

---

## Task 12: Updating Git Branch in Copied Job

### Objective

Configure copied Jenkins job for a new feature branch.

### Requirements

- Open copied Jenkins job configuration  
- Navigate to Source Code Management section  
- Update Git branch name  
- Verify repository URL  
- Save configuration changes  
- Trigger build  
- Verify successful branch build  

---

## Task 13: Updating Environment URLs in pom.xml

### Objective

Update environment-specific integrations for new branch builds.

### Requirements

- Open GitHub repository  
- Switch to feature branch  
- Open pom.xml file  
- Verify SonarQube URL  
- Verify Nexus URL  
- Verify deployment URLs  
- Update incorrect URLs if required  
- Push updated code to GitHub  

---

# Build Trigger Flow

---

## Task 14: Configuring Poll SCM Trigger

### Objective

Automatically trigger builds when Jenkins detects code changes.

### Requirements

- Open Jenkins job configuration  
- Navigate to Build Triggers section  
- Enable Poll SCM option  
- Add cron schedule  
- Save configuration changes  
- Push code changes to GitHub  
- Verify automatic build trigger  

---

## Task 15: Configuring Build Periodically Trigger

### Objective

Run builds on fixed schedules.

### Requirements

- Open Jenkins job configuration  
- Navigate to Build Triggers section  
- Enable Build Periodically option  
- Add cron schedule  
- Save configuration changes  
- Verify scheduled build execution  

---

## Task 16: Configuring GitHub Webhook Trigger

### Objective

Trigger builds immediately after code push.

### Requirements

- Open Jenkins job configuration  
- Enable GitHub webhook trigger  
- Save configuration changes  
- Open GitHub repository settings  
- Navigate to Webhooks section  
- Add Jenkins webhook URL  
- Push code changes  
- Verify automatic build trigger  

---

# Build Maintenance Flow

---

## Task 17: Configuring Discard Old Builds

### Objective

Automatically clean old Jenkins build records.

### Requirements

- Open Jenkins job configuration  
- Enable Discard Old Builds option  
- Configure number of builds to retain  
- Configure number of days to retain builds  
- Configure artifact retention settings  
- Save configuration changes  
- Verify build cleanup settings  

---

## Task 18: Verifying Jenkins Build Storage

### Objective

Understand where Jenkins stores build records.

### Requirements

- Connect to Jenkins server  
- Navigate to Jenkins jobs directory  
- Open specific job folder  
- Navigate to builds folder  
- Verify build storage structure  
- Verify old build folders  

---

# Build Monitoring Flow

---

## Task 19: Configuring Timestamps in Console Output

### Objective

Track execution time of Jenkins build steps.

### Requirements

- Install Timestamper plugin  
- Open Jenkins job configuration  
- Navigate to Build Environment section  
- Enable timestamps option  
- Save configuration changes  
- Trigger build  
- Verify timestamps in console logs  

---

# Code Coverage Flow

---

## Task 20: Configuring JaCoCo Code Coverage

### Objective

Measure code coverage in Jenkins builds.

### Requirements

- Install JaCoCo plugin  
- Open Jenkins job configuration  
- Add post-build action  
- Select JaCoCo coverage report  
- Configure coverage thresholds  
- Trigger build  
- Verify code coverage report generation  
- Verify build behavior for low coverage  

---
