# DevOps Multi-Service Docker Project

## Overview
This project demonstrates containerization and orchestration of two backend services using Docker and Docker Compose:

-  NestJS (Node.js)
-  FastAPI (Python)

Both services are containerized using multi-stage Docker builds and orchestrated through Docker Compose for seamless networking and deployment.

---

##  Tech Stack
- Docker
- Docker Compose
- NestJS
- FastAPI
- Node.js
- Python 3
- Multi-stage Docker builds

---

## Architecture

Two independent services run in isolated containers:

- **NestJS Service**
  - Port: `3000`
  - Health Endpoint: `/health`

- **FastAPI Service**
  - Port: `8000`
  - Swagger Docs: `/docs`

Docker Compose manages:
- Container networking
- Port mapping
- Service orchestration

---

##  How to Run (Run all steps in Bash)

### 1️ Clone Repository

git clone https://github.com/vivekpal1615/devops-multi-service-docker.git
cd devops-multi-service-docker

## 2 Build & Start Containers

docker compose up --build

## 3 Stop Containers

docker compose down
