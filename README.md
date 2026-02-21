#DevOps Assignment

This project contains two applications containerized using Docker and orchestrated using Docker Compose.

##Applications

1. NestJS Application
   - Port: 3000
   - Health Check: http://localhost:3000/health

2. FastAPI Application
   - Port: 8000
   - Swagger Docs: http://localhost:8000/docs

---

##How to Run

Make sure Docker is installed.

###Build and Start

docker compose up --build

###Stop Services

docker compose down

---

##Project Structure

devops-assignment/
│
├── docker-compose.yml
├── README.md
│
├── devops-sample-nest/
│   ├── Dockerfile
│   └── source code
│
└── devops-sample-fast/
    ├── Dockerfile
    └── source code
