# Kubernetes DaemonSet Tasks

## Task 1: Verifying Existing Cluster Nodes for DaemonSet Deployment

### Objective

Understand Node availability before deploying DaemonSet.

### Requirements

- Display available Kubernetes Nodes
- Verify Master Node status
- Verify Worker Node status
- Display Node roles
- Confirm cluster readiness for DaemonSet deployment

---

## Task 2: Identifying Existing DaemonSet Pods in kube-system Namespace

### Objective

Understand real-world DaemonSet usage inside Kubernetes cluster.

### Requirements

- Display all resources in kube-system namespace
- Identify Pods automatically running on all Nodes
- Verify kube-proxy Pods
- Verify weave-net or CNI Pods
- Compare control plane Pods vs DaemonSet Pods
- Confirm understanding of DaemonSet behavior in cluster

---

## Task 3: Creating Basic DaemonSet YAML

### Objective

Create a DaemonSet configuration file.

### Requirements

- Create a file named ds.yaml
- Add apiVersion: apps/v1 in YAML file
- Add kind: DaemonSet in YAML file
- Add metadata configuration with DaemonSet name nginx-ds
- Add namespace configuration as test-ns
- Add selector configuration using matchLabels
- Add label configuration app: nginx
- Add Pod template configuration
- Add nginx container image configuration
- Add containerPort configuration as 80
- Save YAML file
- Verify DaemonSet YAML content

---

## Task 4: Deploying Basic DaemonSet

### Objective

Deploy DaemonSet on cluster Nodes.

### Requirements

- Apply ds.yaml file using kubectl
- Verify DaemonSet creation
- Display available DaemonSets
- Verify desired Pod count
- Verify current Pod count
- Confirm successful DaemonSet deployment

---

## Task 5: Verifying DaemonSet Pod Scheduling Behavior

### Objective

Verify DaemonSet Pod scheduling across cluster Nodes.

### Requirements

- Display Pods with wide output
- Verify Pod-to-Node mapping
- Verify one Pod running on each schedulable Node
- Verify DaemonSet Pod scheduling behavior based on Node taints
- Confirm DaemonSet Pod scheduling behavior understanding

---

## Task 6: Verifying Master Node Taints

### Objective

Understand why DaemonSet Pods are not scheduled on certain Nodes.

### Requirements

- Describe Master Node details
- Verify NoSchedule taint on Master Node
- Describe Worker Node details
- Verify Worker Nodes do not contain NoSchedule taint
- Confirm Master Node taint behavior understanding

---

## Task 7: Updating DaemonSet with Tolerations

### Objective

Allow DaemonSet Pods to run on Master or control-plane Node.

### Requirements

- Delete existing DaemonSet
- Open ds.yaml file
- Add tolerations configuration in Pod spec
- Configure control-plane NoSchedule toleration
- Save YAML file
- Apply updated ds.yaml file using kubectl
- Verify updated DaemonSet deployment

---

## Task 8: Verifying DaemonSet Pods on All Nodes

### Objective

Verify DaemonSet Pods run on Master and Worker Nodes.

### Requirements

- Display Pods with wide output
- Verify Pod scheduling on Master Node
- Verify Pod scheduling on Worker Nodes
- Verify total Pod count equals total Node count
- Confirm successful DaemonSet scheduling on all Nodes

---

## Task 9: Verifying Automatic Pod Scheduling on New Node

### Objective

Understand automatic DaemonSet Pod creation on newly added Nodes.

### Requirements

- Add a new Worker Node to the cluster
- Verify new Node joins Kubernetes cluster
- Display available Nodes
- Verify automatic DaemonSet Pod creation on new Node
- Verify one DaemonSet Pod running on newly added Node
- Confirm automatic DaemonSet scheduling behavior

---

## Task 10: Deleting DaemonSet and Final Validation

### Objective

Understand DaemonSet cleanup and behavior.

### Requirements

- Verify running DaemonSet Pods
- Delete DaemonSet using kubectl
- Verify DaemonSet deletion
- Verify DaemonSet Pods are removed automatically
- Compare DaemonSet behavior with ReplicaSet and Deployment
- Confirm successful DaemonSet management understanding