## Kubernetes Practice

This repository contains my exercises while learning **Kubernetes**.  
I used **Minikube** and **kubectl** to explore core concepts, deployments, scaling, and networking.

### Topics Covered

- Pods, ReplicaSets, and Deployments
- Services (ClusterIP, NodePort, LoadBalancer) and networking between pods
- ConfigMaps and environment variables
- Volumes (ephemeral vs persistent) and PVC management
- Resource requests, limits, and Horizontal Pod Autoscaler (HPA)
- Namespaces and resource organization
- Rolling updates and restarts

### Tools Used

- **Minikube** for local Kubernetes cluster
- **kubectl** for cluster management

### How to Run

```bash
# Start Minikube
minikube start
# Apply all manifests recursively
kubectl apply -R -f .
# Check running pods
kubectl get pods
```
