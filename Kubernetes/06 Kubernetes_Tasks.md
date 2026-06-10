# Kubernetes Deployment Practical Lab Tasks

## Task 1: Verifying Existing Namespace for Deployment Testing

### Objective

Use the existing namespace for Deployment deployment.

### Requirements

* Verify test-ns namespace availability
* Display existing resources in test-ns namespace
* Confirm namespace readiness for Deployment deployment

---

## Task 2: Creating Deployment YAML

### Objective

Create a Kubernetes Deployment configuration file.

### Requirements

* Create a file named deploy.yaml
* Add apiVersion: apps/v1 in YAML file
* Add kind: Deployment in YAML file
* Add metadata configuration with Deployment name javawebappdeploy
* Add namespace configuration as test-ns
* Configure replicas value as 3
* Add selector configuration using matchLabels
* Add Pod template metadata labels app: javawebapp
* Add container image configuration with version 1.0.0
* Add containerPort configuration as 8080
* Save YAML file
* Verify Deployment YAML content

---

## Task 3: Creating NodePort Service for Deployment

### Objective

Expose Deployment application externally using NodePort Service.

### Requirements

* Add Service configuration in deploy.yaml or separate service.yaml
* Configure Service type as NodePort
* Configure selector app: javawebapp
* Configure Service port as 80
* Configure targetPort as 8080
* Configure nodePort value
* Save YAML file
* Verify Service YAML configuration

---

## Task 4: Deploying Kubernetes Deployment

### Objective

Deploy application using Kubernetes Deployment.

### Requirements

* Apply deploy.yaml file using kubectl
* Verify Deployment creation
* Verify ReplicaSet creation
* Verify Pod creation
* Verify NodePort Service creation
* Display all resources in test-ns namespace
* Confirm successful Deployment deployment

---

## Task 5: Verifying Deployment, ReplicaSet, and Pod Relationship

### Objective

Understand Deployment architecture and resource hierarchy.

### Requirements

* Display Deployment details
* Verify desired replica count
* Verify available replica count
* Display ReplicaSet details
* Verify ReplicaSet desired and current Pod count
* Display running Pods
* Verify Pod ownership by ReplicaSet
* Confirm Deployment → ReplicaSet → Pod relationship understanding

---

## Task 6: Verifying External Access Through NodePort Service

### Objective

Verify external application access using NodePort Service.

### Requirements

* Display Service details
* Verify assigned NodePort value
* Verify Service endpoints
* Get Worker Node public IP address
* Access application using NodeIP:NodePort in browser
* Verify successful application response
* Confirm external Service accessibility

---

## Task 7: Verifying Deployment Rollout Status

### Objective

Monitor Deployment rollout progress.

### Requirements

* Execute rollout status command for Deployment
* Verify Deployment successfully rolled out message
* Verify all Pods are in Running state
* Verify Deployment availability status
* Confirm successful rollout completion

---

## Task 8: Scaling Deployment Up

### Objective

Increase the number of application Pods.

### Requirements

* Verify current replica count
* Scale Deployment replicas to 5
* Verify scaling command execution
* Verify new Pods are created automatically
* Verify updated replica count
* Confirm successful scale-up operation

---

## Task 9: Scaling Deployment Down

### Objective

Reduce the number of application Pods.

### Requirements

* Verify current replica count
* Scale Deployment replicas to 2
* Verify extra Pods are terminated automatically
* Verify updated replica count
* Confirm successful scale-down operation

---

## Task 10: Testing Deployment Self-Healing Behavior

### Objective

Verify automatic Pod recreation by Deployment.

### Requirements

* Display running Pods
* Delete one running Pod manually
* Verify Pod removal
* Wait for Deployment response
* Verify automatic recreation of replacement Pod
* Verify desired replica count maintained
* Confirm successful self-healing behavior

---

## Task 11: Configuring Recreate Deployment Strategy

### Objective

Configure Deployment to use Recreate update strategy.

### Requirements

* Open deploy.yaml file
* Add strategy configuration
* Configure strategy type as Recreate
* Save YAML file
* Apply updated Deployment YAML
* Verify Deployment strategy update
* Confirm Recreate strategy configuration

---

## Task 12: Updating Deployment Image Using Recreate Strategy

### Objective

Update application version using Recreate strategy.

### Requirements

* Update container image version from 1.0.0 to 1.0.1
* Save Deployment YAML changes
* Apply updated Deployment YAML
* Verify old Pods terminate completely first
* Verify new Pods are created after old Pod deletion
* Verify new ReplicaSet creation
* Confirm Recreate strategy rollout behavior

---

## Task 13: Verifying Downtime During Recreate Strategy

### Objective

Understand downtime behavior during Recreate rollout.

### Requirements

* Monitor Pods during Deployment update
* Verify old Pods terminate first
* Verify temporary absence of running Pods
* Verify new Pods start after deletion completes
* Verify application downtime during rollout
* Confirm Recreate strategy behavior understanding

---

## Task 14: Verifying Deployment Rollout History and Revisions

### Objective

Track Deployment revisions and rollout history.

### Requirements

* Display Deployment rollout history
* Verify Deployment revision numbers
* Verify old ReplicaSets are retained
* Verify current active ReplicaSet
* Display all resources in test-ns namespace
* Confirm Deployment revision tracking behavior

---

## Task 15: Updating Deployment Multiple Times

### Objective

Understand ReplicaSet creation during multiple Deployment updates.

### Requirements

* Update Deployment image version to 1.0.2
* Apply updated Deployment YAML
* Verify new ReplicaSet creation
* Verify previous ReplicaSet scaled down to 0
* Update Deployment image version to 1.0.3
* Apply updated Deployment YAML
* Verify another new ReplicaSet creation
* Verify only latest ReplicaSet is active
* Confirm Deployment rollout and ReplicaSet versioning behavior

---

## Task 16: Performing Deployment Rollback

### Objective

Rollback Deployment to previous stable version.

### Requirements

* Display Deployment rollout history
* Verify available revision numbers
* Rollback Deployment to previous revision
* Verify current ReplicaSet scaled down automatically
* Verify old ReplicaSet scaled up automatically
* Verify Pods recreated from rollback revision
* Confirm successful Deployment rollback behavior

---

## Task 17: Verifying Rollback Revision Increment Behavior

### Objective

Understand Kubernetes rollback revision management.

### Requirements

* Display Deployment rollout history before rollback
* Perform rollback to older revision
* Display rollout history again
* Verify rollback creates a new revision number
* Verify revision numbers continue increasing
* Confirm Deployment revision behavior understanding

---

## Task 18: Configuring RollingUpdate Deployment Strategy

### Objective

Configure Deployment to use RollingUpdate strategy.

### Requirements

* Open deploy.yaml file
* Remove Recreate strategy configuration
* Configure strategy type as RollingUpdate
* Save YAML file
* Apply updated Deployment YAML
* Verify RollingUpdate strategy configuration

---

## Task 19: Updating Deployment Using RollingUpdate Strategy

### Objective

Update application version with minimal downtime.

### Requirements

* Update Deployment image version
* Apply updated Deployment YAML
* Verify old Pods remain running during update
* Verify new Pods are created gradually
* Verify old Pods terminate one by one
* Monitor rollout progress using rollout status
* Confirm RollingUpdate rollout behavior

---

## Task 20: Verifying Zero Downtime Behavior and Final Validation

### Objective

Understand advantages of RollingUpdate strategy.

### Requirements

* Access application continuously during rollout
* Verify application remains accessible during update
* Verify at least one Pod remains running during rollout
* Compare Recreate vs RollingUpdate behavior
* Verify latest ReplicaSet is active
* Confirm successful zero downtime Deployment strategy behavior
