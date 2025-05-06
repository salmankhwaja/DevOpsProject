# 🚀 DevOps Capstone: Auth Service (Flask + Docker + K8s)

## 🛠 What’s Inside

- **Flask Login API**
- **Dockerized App**
- **Kubernetes Manifests (Minikube Ready)**
- **Azure DevOps Pipeline (Build & Push to Docker Hub)**

## 🔥 Quick Start

1️⃣ Run Locally:

```bash
cd auth-service
docker build -t auth-service .
docker run -p 5000:5000 auth-service
# DevOpsProject
A Repo made for Student for DevOps Project / Bootcamp


kubectl apply -f infra-scripts/k8s/
minikube service auth-service


2️⃣ Kubernetes (Minikube):

bash
Copy
Edit
kubectl apply -f infra-scripts/k8s/
minikube service auth-service
3️⃣ Azure DevOps:

Create Docker Hub Service Connection.

Set your Docker Hub repo name in azure-pipelines.yml.

Run Pipeline!

✅ Your Lab Checklist

 Docker build & run locally

 Push image to Docker Hub

 Kubernetes deploy works locally

 Pipeline runs successfully


---

## 🚀 **Step 3: Push Everything**

You can:

- Clone your repo locally.
- Add folders/files as listed.
- `git add .`
- `git commit -m "Add DevOps capstone files"`
- `git push origin main`

---

👉 **Once your repo is live, share the link here** if you want me to review it or improve anything! 💪
