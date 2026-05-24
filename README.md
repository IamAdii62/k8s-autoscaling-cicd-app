# 🚀 Kubernetes AutoScaling CI/CD Application on AWS EKS

A complete DevOps + Cloud project where a full-stack containerized application was deployed using Kubernetes, AWS EKS, monitoring tools, autoscaling, and GitHub integration.

---

# 📌 Project Overview

This project demonstrates:

- Docker containerization
- Kubernetes deployment
- AWS EKS cluster setup
- Horizontal Pod Autoscaling (HPA)
- Monitoring using Prometheus & Grafana
- GitHub integration
- CI/CD troubleshooting and deployment fixes

---

# 🛠️ Tech Stack

- Docker
- Kubernetes
- Minikube
- AWS EKS
- EC2
- Prometheus
- Grafana
- MongoDB
- React
- Node.js
- Git & GitHub

---

# 📌 Project Flow (Step by Step)

---

# ✅ Step 1 — Project Setup

Created a full-stack application structure:

- Frontend
- Backend API
- MongoDB Database

![Project Structure](screenshots/project-structure.png)
---

# ✅ Step 2 — Docker Containerization

Dockerized all services:

- Frontend container
- Backend container
- MongoDB integration


![Docker Images](screenshots/docker-images.png)

![Docker Images](screenshots/docker-images-1.png)

![Docker Images](screenshots/docker-images-2.png)

![Docker Images](screenshots/docker-images-3.png)

---

# ✅ Step 3 — Kubernetes Deployment on Minikube

Deployed the application on Kubernetes using:

- Deployments
- Services
- ClusterIP
- NodePort

![Kubernetes Pods](screenshots/k8s-pods-1.png)

---

# ✅ Step 4 — Kubernetes Services
Verified Kubernetes services:

- backend-service
- mongo-service
- myapp-service

![Kubernetes Services](screenshots/k8s-services.png)

---

# ✅ Step 5 — Horizontal Pod Autoscaler (HPA)

Configured autoscaling using CPU utilization.

![HPA Autoscaling](screenshots/hpa-autoscaling.png)
---

# ✅ Step 6 — AWS EKS Cluster Setup

Created AWS EKS cluster with:

- Managed Node Group
- EC2 Worker Nodes
- Networking configuration

![EKS Cluster Setup](screenshots/eks-cluster-setup.png)

![EKS Networking](screenshots/eks-networking.png)
---


# ✅ Step 7 — Node Group & EC2 Worker Nodes

Configured worker nodes for Kubernetes workload

![Node Group & Worker Nodes](screenshots/nodegroup-worker-nodes.png)
---

# ✅ Step 8 — LoadBalancer Service

Exposed the application publicly using AWS LoadBalancer.

![LoadBalancer Service](screenshots/loadbalancer-service.png)
---

# ✅ Step 9 — Application Output

Successfully connected:

- Frontend
- Backend
- MongoDB
![Application Output](screenshots/app-output.png)
---

# ✅ Step 10 — Monitoring Setup

Installed monitoring stack using Helm:

- Grafana
- Alertmanager
- Node Exporter
![Monitoring Pods](screenshots/monitoring-pods1.png)

![Monitoring Pods](screenshots/monitoring-pods.png)
---

# ✅ Step 11 — Grafana Dashboard

Configured Grafana dashboard for Kubernetes monitoring.
![Grafana Dashboard](screenshots/grafana-dashboard.png)

![Grafana Dashboard](screenshots/grafana-dashboard-1.png)
---

# ✅ Step 12 — GitHub Integration

Pushed the complete project to GitHub repository.
---

# 🧠 Issues Solved During Project

- LoadBalancer DNS issue
- Grafana login failure
- Monitoring pod restart issue
- Port-forward connection refused
- GitHub push failed because of large files
- Kubernetes context mismatch
- EKS cluster deletion dependency issue
- AWS resource cleanup verification

---

# ⚙️ Useful Commands

## Kubernetes Pods

```bash
kubectl get pods
```
## Kubernetes Services

```bash
kubectl get svc
```
---

## Horizontal Pod Autoscaler (HPA)

```bash
kubectl get hpa
```
---

## Monitoring Namespace Pods

```bash
kubectl get pods -n monitoring
```
---

## Grafana Port Forward

```bash
kubectl port-forward svc/monitoring-grafana -n monitoring 3000:80
```

---

## Check Current Kubernetes Context

```bash
kubectl config current-context
```
---

## Switch Kubernetes Context

```bash
kubectl config use-context minikube
```
---

## AWS EKS Cluster List

```bash
aws eks list-clusters --region ap-south-1
```
---

## AWS EKS Nodegroup List

```bash
aws eks list-nodegroups --cluster-name aditi-cluster --region ap-south-1
```
---

# 📌 Final Output

✔️ Full-stack application deployed successfully on Kubernetes  
✔️ Monitoring stack configured successfully  
✔️ HPA autoscaling working  
✔️ Application exposed using AWS LoadBalancer  
✔️ GitHub repository updated successfully  
✔️ AWS resources cleaned after project completion

---

# 📌 Author

Aditi Kumari  
Cloud Engineer | DevOps | Kubernetes | AWS | Docker
