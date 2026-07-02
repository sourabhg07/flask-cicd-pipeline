# 🚀 Flask CI/CD Pipeline with Docker, GitHub Actions & Render

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-3.x-black?style=for-the-badge&logo=flask)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED?style=for-the-badge&logo=docker)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI-2088FF?style=for-the-badge&logo=githubactions)
![Render](https://img.shields.io/badge/Deploy-Render-46E3B7?style=for-the-badge&logo=render)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

A **production-ready Flask web application** showcasing a complete **CI/CD pipeline** using **GitHub Actions**, **Docker**, **Gunicorn**, and **Render**.

---

# 🌐 Live Demo

👉 **https://flask-cicd-pipeline-lbhl.onrender.com**

---

# 📖 Overview

This project demonstrates how modern applications are developed, tested, containerized, and deployed automatically.

Whenever new code is pushed to GitHub:

- ✅ Code is formatted using Black
- ✅ Code quality is checked using Flake8
- ✅ Unit tests run using Pytest
- ✅ Docker image is built
- ✅ Application is automatically deployed to Render

---

# ✨ Features

- 🚀 Responsive Flask Web Application
- 🐳 Docker Containerization
- ⚙️ GitHub Actions CI Pipeline
- 🧪 Automated Unit Testing (Pytest)
- 📝 Code Formatting (Black)
- ✔️ Code Linting (Flake8)
- 🌍 Production Deployment on Render
- 🔥 Gunicorn Production Server
- ❤️ Health Check API

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python 3.13 |
| Backend | Flask |
| Testing | Pytest |
| Formatting | Black |
| Linting | Flake8 |
| Containerization | Docker |
| CI/CD | GitHub Actions |
| Production Server | Gunicorn |
| Cloud Deployment | Render |
| Version Control | Git & GitHub |

---

# 🏗 CI/CD Architecture

```text
Developer
     │
     ▼
Git Push
     │
     ▼
GitHub Repository
     │
     ▼
GitHub Actions
     │
     ├── Black
     ├── Flake8
     ├── Pytest
     └── Docker Build
     │
     ▼
Render Deployment
     │
     ▼
🌍 Live Website
```

---

# 📂 Project Structure

```text
flask-cicd-pipeline
│
├── .github
│   └── workflows
│       └── ci.yml
│
├── templates
│   └── index.html
│
├── tests
│   └── test_app.py
│
├── app.py
├── Dockerfile
├── requirements.txt
├── .dockerignore
├── .gitignore
└── README.md
```

---

# 📸 Screenshots

## 🏠 Home Page

> Add screenshot here

```
screenshots/home.png
```

---

## ⚙️ GitHub Actions

> Add screenshot here

```
screenshots/github-actions.png
```

---

## 🐳 Docker

> Add screenshot here

```
screenshots/docker.png
```

---

## ☁️ Render Deployment

> Add screenshot here

```
screenshots/render.png
```

---

# ⚙️ Local Installation

## Clone Repository

```bash
git clone https://github.com/sourabhg07/flask-cicd-pipeline.git

cd flask-cicd-pipeline
```

## Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python app.py
```

---

# 🐳 Docker

## Build Docker Image

```bash
docker build -t flask-cicd-pipeline .
```

## Run Container

```bash
docker run -d -p 5000:5000 --name flask-app flask-cicd-pipeline
```

---

# 🧪 Run Tests

```bash
python -m pytest
```

---

# ❤️ Health Check

```text
GET /health
```

Response

```json
{
  "status": "healthy"
}
```

---

# 🚀 CI/CD Workflow

Every push to the **main** branch automatically performs:

- Install Dependencies
- Code Formatting (Black)
- Static Code Analysis (Flake8)
- Unit Testing (Pytest)
- Docker Image Build
- Automatic Deployment to Render

---

# 💡 Learning Outcomes

This project demonstrates practical experience with:

- CI/CD Pipelines
- Docker
- Cloud Deployment
- DevOps Fundamentals
- Production-ready Flask Applications
- GitHub Actions Automation
- Automated Testing
- Production Web Servers

---

# 👨‍💻 Author

**Sourabh Gupta**

- GitHub: https://github.com/sourabhg07

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
