"# My CI/CD Node.js Project" 
# CI/CD Node.js App with GitHub Actions and Docker

## 📌 Overview
Automates testing, Docker image build, and deployment to DockerHub using GitHub Actions.

## 🔧 Tools Used
- Node.js
- Docker & DockerHub
- GitHub Actions

## 🛠️ Setup Steps
1. Initialized Node.js app with a basic HTTP server.
2. Created Dockerfile to containerize the app.
3. Created GitHub Actions workflow at `.github/workflows/main.yml`.
4. Configured GitHub Secrets for DockerHub credentials.
5. Pushed app to GitHub to trigger CI/CD pipeline.

## ⚙️ Pipeline Flow
- Trigger: push to `main` branch
- Jobs:
  - Checkout code
  - Setup Node.js
  - Run tests
  - Build Docker image
  - Log in to DockerHub
  - Push image

## 📦 DockerHub
App image available at: [https://hub.docker.com/r/prithesh/sample-node-app](https://hub.docker.com/r/prithesh/sample-node-app)

