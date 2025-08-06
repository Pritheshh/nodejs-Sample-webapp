# My CI/CD Node.js Project  
# CI/CD Node.js App with GitHub Actions and Docker

## Overview  
This project automates testing, building a Docker image, and deploying to DockerHub using GitHub Actions.

## Tools Used  
- Node.js  
- Docker and DockerHub  
- GitHub Actions  

## Setup Steps  
1. Initialized the Node.js app with a basic HTTP server.  
2. Created a Dockerfile to package the app.  
3. Created a GitHub Actions workflow at `.github/workflows/main.yml`.  
4. Set up GitHub Secrets for DockerHub credentials.  
5. Pushed the app to GitHub to start the CI/CD pipeline.  

## Pipeline Flow  
- Trigger: push to the `main` branch  
- Jobs:  
  - Checkout code  
  - Set up Node.js  
  - Run tests  
  - Build Docker image  
  - Log in to DockerHub  
  - Push image  

## DockerHub  
The app image is available at: [https://hub.docker.com/r/prithesh/sample-node-app](https://hub.docker.com/r/prithesh/sample-node-app)
