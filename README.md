# DockerSandbox

Welcome to **DockerSandbox**, a project designed to learn the fundamentals of Docker and Kubernetes while building and deploying a Django REST API. The initial goal is to master containerization with Docker, gain a high-level understanding of Kubernetes, and prepare for cloud deployment using Microsoft Azure.

---

## Project Goals
The primary objectives are:
- Learn **Docker fundamentals** and containerize a Django REST API.
- Understand the basics of **Kubernetes** for container orchestration.
- Prepare to deploy the application to **Azure** for cloud testing.

---

## Learning Plan

### 1. Learn Docker Basics
- **Objective**: Install Docker and containerize a simple Django REST API project (e.g., a to-do list app).
- **Key Concepts**:
  - Dockerfiles
  - Images
  - Containers
  - Docker Compose (for multi-container setups, e.g., Django + PostgreSQL)
- **Practice**: Write a Dockerfile for a Django REST API and run it locally with `docker run`.

- **Running with Docker Notes**:
  - What exactly is docker??
    - Docker containers are lightweight, standalone, executabe packages of software that include everything needed to run an application.
  - What is the Open Container Initiative (OCI)?
    - OCI is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

### 2. Get a High-Level Kubernetes Overview
- **Objective**: Learn what Kubernetes does (orchestrating containers) without diving into complex setups.
- **Key Concepts**:
  - Pods
  - Deployments
  - Services
- **Focus**: Understand the role of Kubernetes in scaling and managing containers.

### 3. Set Up Your Development Environment
- **Tools**:
  - **VS Code**: Install with extensions for Python, Docker, and Azure.
  - **Cursor** (optional): Explore this AI-powered editor for coding or Docker tasks.
- **Practice**: Use VS Code to write and test Dockerized Django code.

### 4. Practice Locally First
- **Objective**: Build and test a Django REST API locally using Docker.
- **Steps**:
  - Create a simple API (e.g., GET/POST endpoints for a to-do list).
  - Containerize it with Docker.
  - Test locally (e.g., using Postman or `curl`) before considering cloud deployment.

### 5. Prepare for Azure
- **Objective**: Deploy the containerized Django app to Azure (e.g., Azure App Service or Azure Kubernetes Service).
- **Steps**:
  - Gain comfort with Docker locally first.
  - Use Azure credentials (provided later) to deploy from your tools (e.g., VS Code).
- **Focus**: Transition from local testing to cloud deployment.

---

## Recommended Resources

### Docker
- **[Official Docker Getting Started Guide](https://docs.docker.com/get-started/)**  
  Install Docker and run your first container.
- **[Dockerizing a Django Application](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/)**  
  Step-by-step guide to containerize a Django app with PostgreSQL.

### Kubernetes
- **[Kubernetes Tutorial for Beginners](https://www.youtube.com/watch?v=X48VuDVv0do)** (TechWorld with Nana)  
  1-hour overview of Kubernetes concepts (pods, deployments, services).
- **[Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/)**  
  Official guide to core Kubernetes components.

### Azure
- **[Deploy a Django App to Azure](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python)**  
  Microsoft Learn tutorial for deploying Django to Azure App Service.
- **[Azure for Students](https://azure.microsoft.com/en-us/free/students/)**  
  Sign up with a student email for free credits to explore Azure services (e.g., App Service, Container Registry).
- **Practice**: Deploy a containerized Django app to Azure App Service using VS Code (requires credentials later).

### Django REST API Refresher
- **[Django REST Framework Tutorial](https://www.django-rest-framework.org/tutorial/quickstart/)**  
  Official guide to build a simple REST API with models, serializers, and views.

---

## Suggested Timeline (Shouldn't take more than 2-4 weeks so we should be set before end of school year)
- **Week 1: Docker Basics**  
  - Install Docker Desktop.  
  - Containerize a simple Django REST API.  
  - Use Docker Compose with PostgreSQL.  
- **Week 2: Deepen Docker & Kubernetes Intro**  
  - Practice Docker commands (`docker build`, `docker run`, `docker compose up`).  
  - Watch Kubernetes overview video.  
- **Week 3: Local Testing & Tools**  
  - Set up VS Code with Python/Docker extensions.  
  - Test API endpoints locally.  
- **Week 4: Azure Prep**  
  - Explore Azure deployment options.  
  - Prepare to deploy with provided credentials.

---

## Tips for Success
- **Start Small**: Build a minimal Django REST API and containerize it first.
- **Document**: Track progress in this repo (e.g., Dockerfiles, code samples).
- **Practice Explaining**: Be ready to summarize Docker/Kubernetes basics (e.g., “Docker packages apps; Kubernetes manages them at scale”).

---

## Why This Matters
These skills (Docker, Kubernetes, Azure) are industry-standard for deploying Django REST APIs. Mastering them prepares you for internships or projects involving modern web development and cloud deployment.

Happy learning! Contributions or questions? Open an issue or reach out.