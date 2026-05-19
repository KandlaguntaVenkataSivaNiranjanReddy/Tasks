# Jenkins Tasks

## Task 71: Creating Upstream and Downstream Freestyle Jobs
### Objective

Create multiple Jenkins jobs and prepare them for job chaining.

### Requirements

- Login to Jenkins dashboard  
- Create a Freestyle job named bsnl-development  
- Create a Freestyle job named bsnl-QA  
- Create a Freestyle job named bsnl-UAT  
- Verify all three jobs are created successfully  
- Confirm all jobs are visible in Jenkins dashboard  

## Task 72: Configuring Upstream Trigger for QA Job
### Objective

Configure the QA job to start automatically after development job success.

### Requirements

- Open bsnl-QA job configuration  
- Navigate to Build Triggers section  
- Enable Build after other projects are built  
- Add bsnl-development as upstream job  
- Save configuration changes  
- Verify upstream trigger configuration  

## Task 73: Configuring Upstream Trigger for UAT Job
### Objective

Configure the UAT job to start automatically after QA job success.

### Requirements

- Open bsnl-UAT job configuration  
- Navigate to Build Triggers section  
- Enable Build after other projects are built  
- Add bsnl-QA as upstream job  
- Save configuration changes  
- Verify upstream trigger configuration  

## Task 74: Verifying Freestyle Job Chaining
### Objective

Verify automatic sequential execution of linked Jenkins jobs.

### Requirements

- Trigger bsnl-development job manually  
- Verify development job build success  
- Verify automatic triggering of bsnl-QA job  
- Verify QA job build success  
- Verify automatic triggering of bsnl-UAT job  
- Verify full freestyle job chain execution  

## Task 75: Creating Pipeline Jobs for Job Chaining
### Objective

Create pipeline jobs for automated downstream execution.

### Requirements

- Create a Pipeline job named amazon-development  
- Create a Pipeline job named amazon-QA  
- Create a Pipeline job named amazon-UAT  
- Verify all pipeline jobs are created successfully  
- Confirm all jobs are visible in Jenkins dashboard  

## Task 76: Configuring Pipeline Downstream Trigger
### Objective

Trigger downstream jobs inside Jenkins pipeline script.

### Requirements

- Open amazon-development pipeline configuration  
- Add checkout stage in pipeline script  
- Add build stage in pipeline script  
- Use Jenkins build command to trigger amazon-QA job after amazon-development stage  
- Save pipeline configuration  
- Trigger amazon-development job  
- Verify automatic triggering of amazon-QA job  

## Task 77: Configuring Parallel Pipeline Execution
### Objective

Run multiple Jenkins pipeline stages simultaneously.

### Requirements

- Open Jenkins pipeline configuration  
- Add checkout stage in pipeline script  
- Add parallel block in pipeline script  
- Configure Build stage inside parallel block  
- Configure Sonar stage inside parallel block  
- Save pipeline configuration  
- Trigger pipeline build  
- Verify parallel execution in stage view  

## Task 78: Running Build, Sonar, and Nexus in Parallel
### Objective

Execute multiple CI/CD stages simultaneously for faster pipeline execution.

### Requirements

- Open Jenkins pipeline configuration  
- Add parallel execution block  
- Configure Maven build stage  
- Configure SonarQube analysis stage  
- Configure Nexus deployment stage  
- Save pipeline configuration  
- Trigger pipeline build  
- Verify all parallel stages execute successfully  

## Task 79: Configuring Jenkins Shared Library
### Objective

Configure reusable shared library integration in Jenkins.

### Requirements

- Login to Jenkins dashboard  
- Navigate to Manage Jenkins  
- Open Configure System  
- Navigate to Global Pipeline Libraries section  
- Add shared library name  
- Configure Git repository URL  
- Configure branch name  
- Add Git credentials  
- Save shared library configuration  
- Verify successful shared library setup  

## Task 80: Using Shared Library in Jenkins Pipeline
### Objective

Use reusable shared library functions inside Jenkins pipeline.

### Requirements

- Open Jenkins pipeline configuration  
- Load shared library in Jenkinsfile  
- Add pipeline stages for build process  
- Configure post block in pipeline  
- Call shared library Slack notification function  
- Save pipeline configuration  
- Trigger pipeline build  
- Verify successful pipeline execution  
- Verify Slack notification delivery  
- Confirm shared library function execution  
