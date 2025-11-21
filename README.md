# 📦 Multi-Technology Dockerfiles

This repository contains **production-ready Dockerfiles** for multiple application stacks.
Each Dockerfile is placed in its own folder and is designed to be simple, lightweight, and ready for real-world deployments.

---

## 🚀 Technologies Covered

This repo includes Dockerfiles for:

* **Java (Maven → WAR → Tomcat)**
* **Node.js (Express / Backend)**
* **.NET / ASP.NET Core**
* **Python (FastAPI / Flask / Django)**

Each Dockerfile follows best DevOps practices such as:

* Multi-stage builds
* Small and optimized runtime images
* Clear separation between build and execution
* Production-friendly entrypoints
* Ready for CI/CD pipelines (GitHub Actions / Jenkins / Docker Hub)

---

## 📁 Repository Structure

```
/
├── java/
│   └── Dockerfile
├── nodejs/
│   └── Dockerfile
├── dotnet/
│   └── Dockerfile
└── python/
    └── Dockerfile
```

Each folder contains a **fully functional Dockerfile** for that specific technology.

---

## 🧪 How to Build & Run (General Commands)

### Build an image

```sh
docker build -t my-app .
```

### Run a container

```sh
docker run -d -p <port>:<port> my-app
```

### View container logs

```sh
docker logs -f my-app
```

---

## 🎯 Purpose

This repository serves as a **reference collection** for clean, modular Dockerfiles that can be used for:

* Learning Docker
* Setting up CI/CD pipelines
* Deploying microservices
* Cloud & DevOps practice (EC2, Docker Hub, Kubernetes, etc.)
* Portfolio or interview demonstration

