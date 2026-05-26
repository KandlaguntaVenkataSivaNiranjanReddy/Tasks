# Kubernetes Labels & Services Practical Lab Tasks

## Task 11: Creating Namespace for Service Testing

### Objective

Prepare a namespace for Pod and Service deployment.

### Requirements

- Create a namespace named test-ns
- Verify namespace creation
- Display available namespaces
- Confirm namespace readiness for deployment

---

## Task 12: Creating Pods with Labels

### Objective

Deploy Pods with labels for grouping and selection.

### Requirements

- Create a file named nginx-pod.yaml
- Add Pod metadata configuration with Pod name nginx-pod
- Add namespace configuration as test-ns
- Add label configuration app: nginx
- Add nginx container image configuration
- Add containerPort configuration as 80
- Save YAML file
- Apply nginx-pod.yaml file using kubectl
- Verify Pod creation
- Confirm Pod label configuration

---

## Task 13: Creating Another Pod with Different Label

### Objective

Deploy another Pod with separate label for grouping comparison.

### Requirements

- Create a file named mongo-pod.yaml
- Add Pod metadata configuration with Pod name mongo-pod
- Add namespace configuration as test-ns
- Add label configuration app: mongodb
- Add MongoDB container image configuration
- Add containerPort configuration as 27017
- Save YAML file
- Apply mongo-pod.yaml file using kubectl
- Verify Pod creation
- Confirm second Pod label configuration

---

## Task 14: Verifying Pod Labels and Pod IPs

### Objective

Inspect labels and network details of Pods.

### Requirements

- Display Pods with labels
- Verify labels using kubectl get pods -n test-ns --show-labels
- Display Pod details using kubectl describe pod <pod-name> -n test-ns
- Display Pod IP addresses using kubectl get pods -n test-ns -o wide
- Verify node assignment
- Confirm Pod label and network verification

---

## Task 15: Verifying Pod-to-Pod Communication Using Pod IP

### Objective

Test communication between Pods using Pod IP addresses.

### Requirements

- Enter nginx Pod terminal using kubectl exec
- Verify MongoDB Pod IP address
- Test connectivity using ping (if available)
- Or test connectivity to MongoDB Pod IP and port 27017 using telnet or nc
- Verify successful communication response
- Exit Pod terminal
- Confirm Pod-to-Pod communication success

---

## Task 16: Creating ClusterIP Service Using Labels and Selectors

### Objective

Create internal Kubernetes Service for Pod communication.

### Requirements

- Create a file named nginx-clusterip-service.yaml
- Add Service metadata configuration with Service name nginx-clusterip-service
- Add namespace configuration as test-ns
- Add selector configuration app: nginx
- Configure Service port as 80
- Configure targetPort as 80
- Configure Service type as ClusterIP
- Save YAML file
- Apply nginx-clusterip-service.yaml file using kubectl
- Verify Service creation
- Confirm ClusterIP Service deployment

---

## Task 17: Verifying ClusterIP Service and Endpoints

### Objective

Verify Service-to-Pod routing using selectors and endpoints.

### Requirements

- Display available Services
- Verify ClusterIP address
- Describe Service details
- Verify selector configuration
- Verify Service port mapping
- Display Service endpoints
- Verify endpoint Pod IP mapping
- Confirm successful Service routing configuration

---

## Task 18: Creating NodePort Service

### Objective

Expose application externally using NodePort Service.

### Requirements

- Create a file named nginx-nodeport-service.yaml
- Add Service metadata configuration with Service name nginx-nodeport-service
- Add namespace configuration as test-ns
- Add selector configuration app: nginx
- Configure Service port as 80
- Configure targetPort as 80
- Configure nodePort value as 30007
- Configure Service type as NodePort
- Save YAML file
- Apply nginx-nodeport-service.yaml file using kubectl
- Confirm NodePort Service deployment

---

## Task 19: Verifying External Access Using NodePort Service

### Objective

Verify external client access to Kubernetes application.

### Requirements

- Display NodePort Service details
- Verify assigned NodePort value
- Verify Service endpoints
- Get worker node public IP address
- Access application using NodeIP:30007 in browser
- Verify successful application response
- Confirm external Service access

---

## Task 20: Verifying Service Types and Final Validation

### Objective

Understand Kubernetes Service types and traffic routing flow.

### Requirements

- Verify ClusterIP Service behavior
- Verify NodePort Service behavior
- Understand LoadBalancer Service purpose
- Understand ExternalName Service purpose
- Verify relationship between Labels and Selectors
- Verify Endpoint role in traffic routing
- Confirm successful Kubernetes Service management understanding
