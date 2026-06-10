# Kubernetes Requests, Limits & ResourceQuota Practical Lab Tasks

## Task 71: Verifying Node Capacity and Allocatable Resources

### Objective

Understand available cluster resources before scheduling workloads.

### Requirements

- Display available Kubernetes Nodes
- Describe a Worker Node
- Verify CPU capacity
- Verify Memory capacity
- Verify Allocatable CPU resources
- Verify Allocatable Memory resources
- Compare Capacity vs Allocatable resources
- Confirm Node resource availability understanding

---

## Task 72: Verifying Existing Resource Allocation on Nodes

### Objective

Understand how existing workloads consume Node resources.

### Requirements

- Describe a Worker Node
- Locate Non-Terminated Pods section
- Identify running system Pods
- Locate Allocated Resources section
- Verify CPU Requests consumption
- Verify Memory Requests consumption
- Verify configured Limits usage
- Confirm current Node resource utilization understanding

---

## Task 73: Understanding Current Namespace Resource Usage

### Objective

Understand current resource consumption inside the namespace.

### Requirements

- Display resources in test-ns namespace
- Verify current Pod count
- Verify running workloads
- Display Deployments in namespace
- Display Services in namespace
- Confirm current namespace resource usage

---

## Task 74: Creating Deployment with Resource Requests Only

### Objective

Configure guaranteed minimum resources for application Pods.

### Requirements

- Create a file named reqlimit.yaml
- Configure Deployment metadata
- Configure namespace as test-ns
- Configure replicas as 2
- Configure CPU request as 500m
- Configure Memory request as 256Mi
- Do not configure Limits section
- Configure container image
- Save YAML file
- Verify Deployment YAML content

---

## Task 75: Deploying Workload with Resource Requests

### Objective

Verify Pod scheduling using resource requests.

### Requirements

- Apply reqlimit.yaml file using kubectl
- Verify Deployment creation
- Verify ReplicaSet creation
- Verify Pod creation
- Verify Pods are in Running state
- Display Deployment details
- Confirm successful workload deployment

---

## Task 76: Verifying Resource Reservation on Worker Nodes

### Objective

Verify how Requests reserve resources on a Node.

### Requirements

- Describe Worker Node
- Locate Allocated Resources section
- Verify CPU Requests allocation
- Verify Memory Requests allocation
- Verify Limits remain unset
- Compare resource allocation before and after deployment
- Confirm Requests reservation behavior understanding

---

## Task 77: Scaling Deployment and Verifying Scheduler Behavior

### Objective

Understand how Kubernetes scheduler evaluates resource requests.

### Requirements

- Scale Deployment replicas to 3
- Verify scaling operation
- Display running Pods
- Verify scheduler attempts to place new Pods
- Monitor Pod scheduling status
- Verify Deployment status
- Confirm scheduler behavior understanding

---

## Task 78: Verifying Pending Pod Scheduling Failures

### Objective

Understand resource-related scheduling failures.

### Requirements

- Identify Pending Pods if any exist
- Describe Pending Pod details
- Verify scheduling failure reason
- Identify resource-related scheduling constraints
- Verify Node resource availability
- Confirm Pending Pod troubleshooting understanding

---

## Task 79: Updating Deployment with Resource Requests and Limits

### Objective

Configure both guaranteed and maximum resource usage.

### Requirements

- Open reqlimit.yaml file
- Configure CPU request as 500m
- Configure Memory request as 256Mi
- Configure CPU limit as 900m
- Configure Memory limit as 500Mi
- Save YAML changes
- Verify Requests and Limits configuration

---

## Task 80: Deploying Workload with Resource Limits

### Objective

Verify workload behavior with resource limits.

### Requirements

- Apply updated reqlimit.yaml file using kubectl
- Verify Deployment rollout
- Verify Pods are running successfully
- Verify updated Deployment configuration
- Verify resource settings are applied
- Confirm successful workload deployment

---

## Task 81: Verifying Requests and Limits in Node Allocation

### Objective

Verify how Kubernetes tracks Requests and Limits.

### Requirements

- Describe Worker Node
- Locate Allocated Resources section
- Verify CPU Requests allocation
- Verify CPU Limits allocation
- Verify Memory Requests allocation
- Verify Memory Limits allocation
- Confirm Requests and Limits tracking behavior

---

## Task 82: Understanding CPU Throttling, OOMKilled, and CrashLoopBackOff Behavior

### Objective

Understand Kubernetes resource enforcement mechanisms.

### Requirements

- Review configured resource limits
- Understand CPU throttling behavior
- Understand Memory limit enforcement behavior
- Review OOMKilled concept
- Review CrashLoopBackOff behavior caused by repeated failures
- Understand impact of insufficient Memory limits on applications
- Confirm resource limit enforcement understanding

---

## Task 83: Fixing Resource Limit Issues by Updating Limits

### Objective

Resolve application failures caused by insufficient limits.

### Requirements

- Review existing resource limits
- Increase Memory limit value
- Increase CPU limit value if required
- Apply updated Deployment YAML
- Verify Pod recreation
- Verify Pods enter Running state
- Verify application stability
- Confirm successful resource tuning

---

## Task 84: Creating ResourceQuota for Namespace

### Objective

Restrict resource consumption within a namespace.

### Requirements

- Create a file named resource-quota.yaml
- Configure ResourceQuota metadata
- Configure namespace as test-ns
- Configure Pod quota limit as 10
- Save YAML file
- Verify ResourceQuota YAML content

---

## Task 85: Deploying and Verifying ResourceQuota

### Objective

Apply ResourceQuota and verify namespace limits.

### Requirements

- Apply resource-quota.yaml file using kubectl
- Verify ResourceQuota creation
- Describe ResourceQuota details
- Verify configured Pod quota limit
- Verify current quota usage
- Confirm successful ResourceQuota deployment

---

## Task 86: Creating Pods and Tracking ResourceQuota Usage

### Objective

Verify ResourceQuota usage tracking.

### Requirements

- Create a Pod manually using kubectl run or Pod YAML
- Verify Pod creation
- Describe ResourceQuota details
- Verify used Pod count increases
- Verify remaining quota decreases
- Confirm ResourceQuota usage tracking behavior

---

## Task 87: Exceeding ResourceQuota Limits and Verifying Enforcement

### Objective

Verify Kubernetes ResourceQuota enforcement.

### Requirements

- Create additional Pods manually using kubectl run or Pod YAML
- Reach configured Pod quota limit
- Attempt creating one additional Pod
- Verify ResourceQuota rejection behavior
- Verify Forbidden error message
- Confirm ResourceQuota enforcement behavior

---

## Task 88: Verifying Requests, Limits, Scheduling, and ResourceQuota Behavior

### Objective

Understand complete Kubernetes resource management flow.

### Requirements

- Verify Requests behavior
- Verify Limits behavior
- Verify Pod scheduling behavior
- Verify Pending Pod behavior
- Verify ResourceQuota behavior
- Compare Requests vs Limits
- Compare Requests vs ResourceQuota
- Confirm successful Kubernetes resource management understanding