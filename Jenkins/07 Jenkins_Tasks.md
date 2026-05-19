# Jenkins Tasks

---

## Task 61: Creating Multibranch Pipeline Job

### Objective

Create a Jenkins Multibranch Pipeline project.

### Requirements

- Login to Jenkins dashboard  
- Click on New Item  
- Enter Multibranch pipeline job name  
- Select Multibranch Pipeline project type  
- Create the job  
- Verify Multibranch pipeline job creation  

---

## Task 62: Configuring Git Branch Source

### Objective

Connect Multibranch Pipeline with Git repository.

### Requirements

- Open Multibranch pipeline configuration  
- Navigate to Branch Sources section  
- Click Add Source  
- Select Git option  
- Add Git repository URL  
- Add Git credentials if repository is private  
- Save configuration changes  

---

## Task 63: Configuring Jenkinsfile Path

### Objective

Configure pipeline script detection for each branch.

### Requirements

- Open Multibranch pipeline configuration  
- Verify default Jenkinsfile path  
- Configure custom Jenkinsfile path if required  
- Save configuration changes  
- Verify pipeline script path configuration  

---

## Task 64: Scanning Branches and Triggering Builds

### Objective

Automatically detect branches and trigger builds.

### Requirements

- Open Scan Multibranch Pipeline Triggers section  
- Configure automatic scan trigger  
- Save configuration changes  
- Run manual scan  
- Verify branch discovery process  
- Verify automatic build creation for valid branches  

---

## Task 65: Verifying Branch-Based Job Creation

### Objective

Verify pipeline creation for branches containing Jenkinsfile.

### Requirements

- Verify available Git branches  
- Identify branches containing Jenkinsfile  
- Verify automatic job creation for valid branches  
- Verify skipped branches without Jenkinsfile  
- Verify automatic build scheduling  

---

## Task 66: Creating New QA Branch

### Objective

Verify automatic branch detection for newly created branches.

### Requirements

- Open GitHub repository  
- Create QA branch from development branch  
- Verify Jenkinsfile availability in QA branch  
- Push branch changes  
- Trigger branch scan  
- Verify automatic QA pipeline creation  
- Verify automatic build execution  

---

## Task 67: Verifying Branch Deletion Handling

### Objective

Verify automatic cleanup for deleted branches.

### Requirements

- Delete an existing branch from GitHub  
- Trigger Multibranch scan  
- Verify branch removal from Jenkins  
- Remove Jenkinsfile from another branch  
- Trigger scan again  
- Verify skipped branch behavior  

---

## Task 68: Performing Manual Jenkins Backup

### Objective

Create manual backup of Jenkins configuration.

### Requirements

- Connect to Jenkins server  
- Stop Jenkins service  
- Copy Jenkins home directory to backup location  
- Verify backup folder creation  
- Start Jenkins service  
- Verify Jenkins accessibility  

---

## Task 69: Configuring ThinBackup Plugin

### Objective

Automate Jenkins backup using ThinBackup plugin.

### Requirements

- Install ThinBackup plugin  
- Navigate to Configure System  
- Configure backup directory path  
- Create backup folder in server  
- Provide folder permissions  
- Configure backup retention settings  
- Save configuration changes  

---

## Task 70: Running Restore and Automated Backup

### Objective

Verify backup restoration and scheduled backup automation.

### Requirements

- Run manual backup using ThinBackup  
- Verify backup files  
- Configure scheduled backup CRON expression  
- Trigger backup job manually  
- Verify automatic backup creation  
- Perform restore operation  
- Verify successful Jenkins recovery  

---
