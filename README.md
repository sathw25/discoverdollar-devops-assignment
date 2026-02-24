# MEAN Stack DevOps Assignment

## Tech Stack
- MongoDB, Express, Angular, Node.js
- Docker & Docker Compose
- GitHub Actions CI/CD
- Azure Ubuntu VM
- Nginx Reverse Proxy

## Infrastructure
- Cloud: Microsoft Azure
- VM IP: 98.70.44.20
- App URL: http://98.70.44.20

## Setup & Deployment

### 1. Clone the repo
```bash
git clone https://github.com/sathw25/discoverdollar-devops-assignment
```

### 2. Docker Compose
```bash
docker compose up -d
```

### 3. CI/CD Pipeline
- GitHub Actions automatically builds and pushes Docker images on every push to main
- Self-hosted runner on Azure VM handles deployment
- Images hosted on Docker Hub: sath10108/mean-backend, sath10108/mean-frontend

### 4. Nginx
- Nginx installed on VM as reverse proxy
- App accessible on port 80

## Docker Hub
- Backend: sath10108/mean-backend
- Frontend: sath10108/mean-frontend
