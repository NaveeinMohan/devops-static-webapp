# 🚀 Static Website Deployment with Docker, Kubernetes, and Argo CD

## 📦 Project Overview
This project demonstrates a complete DevOps pipeline for deploying a static website using Docker, Kubernetes, and GitOps with Argo CD. It includes CI/CD integration, infrastructure as code, and automated deployment workflows.

## 🛠️ Tools & Technologies
- Docker
- Kubernetes
- Argo CD
- GitHub Actions / Jenkins
- YAML
- Git


## 🚀 Deployment Flow
1. Docker image is built and pushed to Docker Hub.
2. Kubernetes manifests are stored in GitHub.
3. Argo CD syncs the manifests and deploys the app.
4. NodePort exposes the app at `http://localhost:30080`.

## 📸 Screenshots
_Add screenshots of Argo CD UI, pod status, and website in browser._

## 🔄 CI/CD Integration
_Describe how GitHub Actions or Jenkins automates builds and deployments._

## 📊 Monitoring (Optional)
_Explain how Prometheus and Grafana can be added for observability._

## 📌 How to Run Locally
```bash
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/guestbook-ui-service.yaml


---

## 🔁 Step 2: Set Up GitHub Actions

Want me to generate a working `ci-cd.yaml` workflow that:
- Builds your Docker image
- Pushes it to Docker Hub
- Updates your Kubernetes manifests?

---

## 🧪 Step 3: Jenkins Pipeline

If you prefer Jenkins, I can help you write a `Jenkinsfile` that:
- Builds and pushes the Docker image
- Triggers Argo CD sync via CLI or webhook

---

## 📊 Step 4: Monitoring with Prometheus & Grafana

I’ll guide you to:
- Install Prometheus and Grafana via Helm
- Configure dashboards to monitor your app

---

Which one do you want to start with — GitHub Actions or Jenkins? Or shall we polish the README first?
