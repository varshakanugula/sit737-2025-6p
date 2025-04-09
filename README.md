# SIT737 2025 Practical 6P – Deploying Node.js to Kubernetes

This project demonstrates how to deploy a simple Node.js Express app to a local Kubernetes cluster using Docker Desktop.

## 📦 Project Structure

sit737-2025-6p/ ├── app.js ├── package.json ├── Dockerfile ├── deployment.yaml ├── service.yaml └── README.md

2. Deploy to Kubernetes
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

3. Access the App
Go to http://localhost:30007

Tech Stack

Node.js
Express.js
Docker
Kubernetes (via Docker Desktop)


---

## 📤 Step 13: Push Everything to GitHub

Make sure your GitHub repo is set up. Then run:

```bash
git add .
git commit -m "Completed SIT737 Practical 6P - Node.js on Kubernetes"
git push origin main


