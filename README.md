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

```md
C:\Users\anari\OneDrive\Pictures\Screenshots\Screenshot 2026-05-23 004849.png
```

---

# ✅ Step 2 — Docker Containerization

Dockerized all services:

- Frontend container
- Backend container
- MongoDB integration

### 📸 Screenshot

```md
![Docker Images](screenshots/docker-images.png)
```

---

# ✅ Step 3 — Kubernetes Deployment on Minikube

Deployed the application on Kubernetes using:

- Deployments
- Services
- ClusterIP
- NodePort

### 📸 Screenshot

```md
![Kubernetes Pods](screenshots/k8s-pods.png)
```

---

# ✅ Step 4 — Kubernetes Services

Verified Kubernetes services:

- backend-service
- mongo-service
- myapp-service

### 📸 Screenshot

```md
![Kubernetes Services](screenshots/k8s-services.png)
```

---

# ✅ Step 5 — Horizontal Pod Autoscaler (HPA)

Configured autoscaling using CPU utilization.

### 📸 Screenshot

```md
![HPA](screenshots/hpa.png)
```

---

# ✅ Step 6 — AWS EKS Cluster Setup

Created AWS EKS cluster with:

- Managed Node Group
- EC2 Worker Nodes
- Networking configuration

### 📸 Screenshot

```md
![EKS Cluster](screenshots/eks-cluster.png)
```

---

# ✅ Step 7 — Node Group & EC2 Worker Nodes

Configured worker nodes for Kubernetes workloads.

### 📸 Screenshot

```md
![Node Group](screenshots/nodegroup.png)
```

### 📸 Screenshot

```md
![EC2 Worker Node](screenshots/ec2-worker.png)
```

---

# ✅ Step 8 — LoadBalancer Service

Exposed the application publicly using AWS LoadBalancer.

### 📸 Screenshot

```md
![LoadBalancer](screenshots/loadbalancer.png)
```

---

# ✅ Step 9 — Application Output

Successfully connected:

- Frontend
- Backend
- MongoDB

### 📸 Screenshot

```md
![Application Output](screenshots/app-output.png)
```

---

# ✅ Step 10 — Monitoring Setup

Installed monitoring stack using Helm:

- Prometheus
- Grafana
- Alertmanager
- Node Exporter

### 📸 Screenshot

```md
![Monitoring Pods](screenshots/monitoring-pods.png)
```

---

# ✅ Step 11 — Grafana Dashboard

Configured Grafana dashboard for Kubernetes monitoring.

### 📸 Screenshot

```md
![Grafana Dashboard](screenshots/grafana-dashboard.png)
```

---

# ✅ Step 12 — GitHub Integration

Pushed the complete project to GitHub repository.

### 📸 Screenshot

```md
![GitHub Repository](screenshots/github-repo.png)
```

---

# ✅ Step 13 — CI/CD Pipeline Debugging

Worked on multiple deployment and CI/CD fixes:

- Retry pipeline
- Auto deploy fix
- Git cleanup
- GitHub large file issue

### 📸 Screenshot

```md
![Git Commits](screenshots/git-commits.png)
```

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

### 📸 Screenshot

```md
![Kubernetes Pods Command](screenshots/kubectl-get-pods.png)
```

---

## Kubernetes Services

```bash
kubectl get svc
```

### 📸 Screenshot

```md
![Kubernetes Services Command](screenshots/kubectl-get-svc.png)
```

---

## Horizontal Pod Autoscaler (HPA)

```bash
kubectl get hpa
```

### 📸 Screenshot

```md
![HPA Command](screenshots/kubectl-get-hpa.png)
```

---

## Monitoring Namespace Pods

```bash
kubectl get pods -n monitoring
```

### 📸 Screenshot

```md
![Monitoring Pods Command](screenshots/monitoring-pods-command.png)
```

---

## Grafana Port Forward

```bash
kubectl port-forward svc/monitoring-grafana -n monitoring 3000:80
```

### 📸 Screenshot

```md
![Grafana Port Forward](screenshots/grafana-portforward.png)
```

---

## Check Current Kubernetes Context

```bash
kubectl config current-context
```

### 📸 Screenshot

```md
![Current Context](screenshots/current-context.png)
```

---

## Switch Kubernetes Context

```bash
kubectl config use-context minikube
```

### 📸 Screenshot

```md
![Switch Context](screenshots/switch-context.png)
```

---

## AWS EKS Cluster List

```bash
aws eks list-clusters --region ap-south-1
```

### 📸 Screenshot

```md
![EKS Cluster List](screenshots/eks-list-clusters.png)
```

---

## AWS EKS Nodegroup List

```bash
aws eks list-nodegroups --cluster-name aditi-cluster --region ap-south-1
```

### 📸 Screenshot

```md
![NodeGroup List](screenshots/nodegroup-list.png)
```

---

## Git Status

```bash
git status
```

### 📸 Screenshot

```md
![Git Status](screenshots/git-status.png)
```

---

## Git Push

```bash
git push origin main
```

### 📸 Screenshot

```md
![Git Push](screenshots/git-push.png)
```

---

# 🔗 GitHub Repository

Repository:

https://github.com/IamAdii62/k8s-autoscaling-cicd-app

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
