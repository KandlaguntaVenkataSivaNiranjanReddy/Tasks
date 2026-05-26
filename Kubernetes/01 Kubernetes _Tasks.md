# Kubernetes Pod Practical Lab Tasks

## Task 1: Verifying Kubernetes Cluster and Nodes

### Objective

Verify Kubernetes cluster readiness before creating pods.

### Requirements

- Connect to Kubernetes master node
- Verify kubectl command availability
- Verify Kubernetes cluster information
- Display available nodes in the cluster
- Verify node status
- Confirm cluster readiness for pod deployment

---

## Task 2: Exploring Kubernetes Namespaces

### Objective

Understand namespace-based logical separation in Kubernetes.

### Requirements

- Display available namespaces
- Verify default namespace
- Verify kube-system namespace
- Identify system pods running in kube-system namespace
- Confirm namespace understanding for pod deployment

---

## Task 3: Creating First Single-Container Pod YAML

### Objective

Create a basic Pod configuration file using YAML.

### Requirements

- Create a file named pod.yaml
- Add apiVersion: v1 in YAML file
- Add kind: Pod in YAML file
- Add metadata section with pod name
- Add spec section with container definition
- Add nginx container image configuration
- Add container port configuration
- Save YAML file
- Verify Pod YAML content

---

## Task 4: Deploying Single-Container Pod

### Objective

Create and run a pod in Kubernetes cluster.

### Requirements

- Apply pod.yaml file using kubectl
- Verify Pod creation using kubectl get pods
- Display available pods
- Verify pod scheduling on worker node
- Verify Pod running status
- Confirm successful Pod deployment

---

## Task 5: Verifying Pod Details and Logs

### Objective

Inspect Pod runtime details and logs.

### Requirements

- Display Pod list using kubectl get pods
- Display Pod details using kubectl describe pod
- Verify Pod IP address
- Verify worker node assignment
- Check Pod container logs
- Confirm successful Pod runtime verification

---

## Task 6: Accessing Pod Container Using exec

### Objective

Enter inside a running Pod for debugging.

### Requirements

- Execute kubectl exec command
- Enter Pod interactive shell
- Verify running processes inside container
- Check container files
- Execute commands like ls, pwd, and ps inside Pod
- Exit Pod terminal
- Confirm successful Pod shell access

---

## Task 7: Creating Multi-Container Pod

### Objective

Deploy a pod with multiple containers.

### Requirements

- Create multi-pod.yaml file
- Add Pod metadata configuration
- Add first application container configuration
- Add second busybox helper container configuration
- Save YAML file
- Apply YAML file using kubectl
- Verify Pod creation
- Verify both containers running inside Pod
- Confirm successful multi-container Pod deployment

---

## Task 8: Verifying Multi-Container Pod Communication and Logs

### Objective

Verify behavior of multiple containers inside same Pod.

### Requirements

- Display Pod details
- Verify both container names
- Check logs of first container
- Check logs of second container
- Enter first container using exec
- Verify shared network namespace inside Pod
- Test communication using localhost if service is exposed
- Confirm shared Pod networking behavior

---

## Task 9: Deleting and Recreating Pods

### Objective

Understand Pod ephemeral behavior in Kubernetes.

### Requirements

- Delete running Pod manually
- Verify Pod removal
- Recreate Pod using YAML file
- Verify new Pod creation
- Verify new Pod IP address
- Confirm Pod ephemeral lifecycle behavior

---

## Task 10: Troubleshooting Pod Status and Final Validation

### Objective

Verify Pod lifecycle states and debug common issues.

### Requirements

- Display Pod status
- Verify Running Pod state
- Describe Pod events
- Check logs for troubleshooting
- Verify Pod restart count
- Verify Pod events for failure reason analysis
- Identify possible Pod states (Pending, Running, CrashLoopBackOff, Failed)
- Confirm successful Pod management understanding

---