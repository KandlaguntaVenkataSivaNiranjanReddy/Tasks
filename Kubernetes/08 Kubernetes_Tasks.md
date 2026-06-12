# Kubernetes Horizontal Pod Autoscaler (HPA) Practical Lab Tasks

## Task 89: Verifying Metrics Availability

### Objective

Verify whether Kubernetes cluster metrics are available for HPA.

### Requirements

- Execute kubectl top nodes command
- Execute kubectl top pods command
- Verify metrics availability
- Identify metrics-related errors if present
- Confirm Metrics Server installation requirement

---

## Task 90: Installing Metrics Server

### Objective

Enable Kubernetes resource metrics collection.

### Requirements

- Install Metrics Server using official Kubernetes manifest
- Verify Metrics Server deployment creation
- Verify Metrics Server Pod creation
- Display resources in kube-system namespace
- Confirm Metrics Server installation

---

## Task 91: Troubleshooting Metrics Server Issues

### Objective

Resolve common Metrics Server startup issues.

### Requirements

- Verify Metrics Server Pod status
- Identify Metrics Server Pod showing 0/1 Ready status
- Edit Metrics Server deployment configuration
- Configure required kubelet arguments
- Save deployment changes
- Verify new Metrics Server rollout
- Confirm healthy Metrics Server Pod status

---

## Task 92 : Verifying Cluster Metrics

### Objective

Verify successful metrics collection.

### Requirements

- Execute kubectl top nodes command
- Verify Node CPU utilization
- Verify Node Memory utilization
- Execute kubectl top pods command
- Verify Pod CPU utilization
- Verify Pod Memory utilization
- Confirm Metrics Server functionality

---

## Task 93: Creating HPA Demo Deployment

### Objective

Deploy an application suitable for HPA testing.

### Requirements

- Create a file named hpa-demo.yaml
- Configure Deployment metadata
- Configure Deployment name as hpadeployment
- Configure Pod labels
- Configure container image
- Configure CPU requests and limits
- Configure Memory requests and limits
- Save Deployment YAML configuration

---

## Task 94: Creating Horizontal Pod Autoscaler Configuration

### Objective

Configure automatic Pod scaling based on resource usage.

### Requirements

- Add HorizontalPodAutoscaler configuration
- Configure scaleTargetRef for Deployment
- Configure minReplicas as 2
- Configure maxReplicas as 4
- Configure CPU utilization target as 30%
- Configure Memory utilization target as 80%
- Save HPA configuration
- Verify HPA YAML content

---

## Task 95: Creating ClusterIP Service for HPA Testing

### Objective

Expose application internally for load generation.

### Requirements

- Add ClusterIP Service configuration
- Configure Service name as hpaclusterservice
- Configure selector labels
- Configure Service port mapping
- Save Service configuration
- Verify Service YAML content

---

## Task 96: Deploying Application, Service, and HPA

### Objective

Deploy all HPA-related resources.

### Requirements

- Apply hpa-demo.yaml file using kubectl
- Verify Deployment creation
- Verify ReplicaSet creation
- Verify Pod creation
- Verify Service creation
- Verify HPA creation
- Confirm successful resource deployment

---

## Task 97: Verifying Initial HPA Status

### Objective

Understand HPA monitoring behavior before load generation.

### Requirements

- Display Horizontal Pod Autoscaler details
- Verify Deployment association
- Verify CPU utilization metrics
- Verify Memory utilization metrics
- Verify minReplicas value
- Verify maxReplicas value
- Verify current replica count
- Confirm HPA monitoring behavior

---

## Task 98: Monitoring Pods and HPA in Real Time

### Objective

Observe HPA behavior during scaling activities.

### Requirements

- Open separate terminal sessions
- Monitor Pods continuously
- Monitor HPA continuously
- Observe current replica count
- Observe CPU utilization changes
- Observe Memory utilization changes
- Confirm monitoring setup readiness

---

## Task 99: Creating Load Generator Pod

### Objective

Generate traffic against the application.

### Requirements

- Launch temporary BusyBox Pod
- Verify BusyBox Pod creation
- Enter BusyBox interactive shell
- Verify Service accessibility
- Confirm load generator readiness

---

## Task 100: Generating Continuous Application Load

### Objective

Increase application resource usage.

### Requirements

- Execute continuous request loop against Service
- Generate traffic using BusyBox Pod
- Verify application request processing
- Monitor application response
- Maintain continuous workload generation
- Confirm load generation activity

---

## Task 101: Verifying HPA Scale-Up Behavior

### Objective

Verify automatic scaling during increased demand.

### Requirements

- Monitor HPA metrics
- Verify CPU utilization increase
- Verify Memory utilization increase
- Verify replica count increase
- Verify new Pods enter ContainerCreating state
- Verify new Pods enter Running state
- Confirm automatic scale-up behavior

---

## Task 102: Verifying Maximum Replica Enforcement

### Objective

Verify HPA scaling limits.

### Requirements

- Continue workload generation
- Monitor replica count growth
- Verify scaling does not exceed maxReplicas value
- Verify maximum Pod count as 4
- Confirm HPA maximum replica enforcement

---

## Task 103: Stopping Load Generation

### Objective

Reduce application demand.

### Requirements

- Stop BusyBox workload execution
- Exit BusyBox shell
- Verify load generator Pod removal
- Verify traffic reduction
- Confirm workload termination

---

## Task 104: Verifying HPA Scale-Down Behavior

### Objective

Verify automatic reduction of Pods during low demand.

### Requirements

- Monitor HPA metrics
- Verify CPU utilization decrease
- Verify Memory utilization decrease
- Verify gradual Pod termination
- Verify replica count reduction
- Verify minimum replica count maintenance
- Confirm automatic scale-down behavior

---

## Task 105: Comparing Manual Scaling and HPA

### Objective

Understand differences between manual and automatic scaling.

### Requirements

- Review kubectl scale command behavior
- Review HPA scaling behavior
- Compare manual scaling process
- Compare automatic scaling process
- Understand scale-out behavior
- Understand scale-in behavior
- Confirm HPA advantages understanding

---

## Task 106: Verifying Complete HPA Lifecycle and Final Validation

### Objective

Understand end-to-end HPA workflow.

### Requirements

- Verify Metrics Server functionality
- Verify Deployment scaling behavior
- Verify HPA monitoring behavior
- Verify scale-up operation
- Verify scale-down operation
- Verify minReplicas enforcement
- Verify maxReplicas enforcement
- Confirm successful HPA implementation understanding

---