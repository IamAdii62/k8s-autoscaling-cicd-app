
# 🚀 Kubernetes AutoScaling CI/CD Full-Stack DevOps Project

A complete end-to-end DevOps project demonstrating containerization, Kubernetes deployment, autoscaling, CI/CD workflow, and monitoring using Prometheus & Grafana on Minikube (with AWS EKS readiness).

---

# 📌 Project Overview

This project demonstrates a full DevOps lifecycle:

- Full-stack application (Frontend + Backend + MongoDB)
- Docker containerization
- Kubernetes deployment (Minikube / EKS-ready)
- Service networking (ClusterIP + NodePort + Ingress)
- Horizontal Pod Autoscaling (HPA)
- Monitoring with Prometheus & Grafana
- GitHub-based CI/CD pipeline
- Real troubleshooting & fixes (production-like issues)

---

# 🛠️ Tech Stack

- Docker
- Kubernetes (Minikube)
- AWS EKS (architecture ready)
- Node.js
- React
- MongoDB
- Helm
- Prometheus
- Grafana
- Git & GitHub

---

# 📌 Architecture Overview

![Project Structure](screenshots/project-structure.png)

---

# 🐳 Step 2 — Docker Containerization

- Created Docker images for frontend & backend
- Pushed images to Docker Hub
- Connected MongoDB service inside cluster

## Docker Images

![Docker Image 1](screenshots/docker-images.png)

![Docker Image 2](screenshots/docker-images-1.png)

![Docker Image 3](screenshots/docker-images-2.png)

![Docker Image 4](screenshots/docker-images-3.png)

---

# ☸️ Step 3 — Kubernetes Deployment (Minikube)

- Deployments created for frontend, backend, MongoDB
- Services configured (ClusterIP + NodePort)
- Pods running successfully

## Kubernetes Pods

![Kubernetes Pods](screenshots/k8s-pods-1.png)

---

# 🔌 Step 4 — Kubernetes Services

Services configured:

- backend-service (ClusterIP)
- mongo-service (ClusterIP)
- myapp-service (NodePort)

## Kubernetes Services

![Kubernetes Services](screenshots/k8s-services.png)

---

# 📈 Step 5 — Horizontal Pod Autoscaler (HPA)

- CPU-based autoscaling configured
- Min pods: 2 | Max pods: 6

## HPA Autoscaling

![HPA Autoscaling](screenshots/hpa-autoscaling.png)

---

# ☁️ Step 6 — AWS EKS (Architecture Ready)

- EKS Cluster setup (theoretical + optional deployment)
- Managed Node Groups
- EC2 Worker Nodes
- Networking configuration

## EKS Cluster Setup

![EKS Cluster Setup](screenshots/eks-cluster-setup.png)

## EKS Networking

![EKS Networking](screenshots/eks-networking.png)

## Worker Node Group

![Worker Nodes](screenshots/nodegroup-worker-nodes.png)

---
# 🌐 Step 7 — Load Balancer / Exposure

- Application exposed using NodePort & Ingress
- Minikube tunnel used for local access

## LoadBalancer Service

![LoadBalancer Service](screenshots/loadbalancer-service.png)

---

# 🧠 Step 8 — Application Output

- Frontend + Backend + MongoDB integration successful
- API communication verified inside cluster

## Application Output

![App Output](screenshots/app-output.png)

---

# 📊 Step 9 — Monitoring (Prometheus + Grafana)

Installed via Helm:

- Prometheus Operator
- Grafana Dashboard
- Node Exporter
- kube-state-metrics

---

## Prometheus Dashboard

Access Prometheus Graph:
- URL: http://<your-server-ip>:9090/graph


## Prometheus Targets

- Endpoint health monitoring:
  http://<server-ip>:9090/targets

## Monitoring - Kubernetes Pods

![Monitoring Pods](screenshots/monitoring-pods.png)

![Monitoring Pods 2](screenshots/monitoring-pods1.png)

---

## Grafana Dashboards

![Grafana Dashboard 1](screenshots/grafana-dashboard.png)

![Grafana Dashboard 2](screenshots/grafana-dashboard-1.png)


---

# ⚙️ Useful Kubernetes Commands

```bash
kubectl get pods
kubectl get svc
kubectl get hpa
kubectl get ingress
kubectl get ns
kubectl port-forward svc/monitoring-grafana -n monitoring 3000:80

```

---

### 🚨 Issues Fixed During Project

Docker driver issue in Minikube (Windows fix)
Kubernetes API version mismatch
NodePort access issues
Prometheus 404 path confusion
Ingress tunnel handling
Service discovery issues
HPA CPU scaling verification
Backend connection debugging

---
## 🎯 Final Result

✔ Full-stack app deployed on Kubernetes
✔ Backend–Frontend–MongoDB connected
✔ HPA autoscaling working
✔ Monitoring stack (Prometheus + Grafana) running
✔ CI/CD pipeline integrated via GitHub
✔ Production-level troubleshooting completed

### 👩‍💻 Author

Aditi Kumari
Cloud Engineer | DevOps | Kubernetes | AWS | Docker


