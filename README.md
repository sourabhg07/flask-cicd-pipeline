# 🚀 Flask CI/CD Pipeline with GitHub Actions & Docker

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Flask](https://img.shields.io/badge/Flask-3.x-green)
![Docker](https://img.shields.io/badge/Docker-Enabled-blue)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI-success)

A production-ready Flask application demonstrating modern DevOps practices including automated testing, code quality checks, GitHub Actions CI, and Docker containerization.

---
# Flask CI/CD Pipeline

## 🚀 Live Demo

https://flask-cicd-pipeline-lbhl.onrender.com

# 📌 Features

- Flask Web Application
- Automated Unit Testing (Pytest)
- Code Formatting (Black)
- Code Linting (Flake8)
- Docker Containerization
- GitHub Actions CI Pipeline
- Health Check API
- HTML Template Rendering

---

# 🛠 Tech Stack

- Python 3.13
- Flask
- Git
- GitHub
- GitHub Actions
- Docker
- Pytest
- Black
- Flake8

---

# 📂 Project Structure

```
CI-CD-Pipeline-Demo
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
├── .gitignore
└── README.md
```

---

# ⚙️ Installation

```bash
git clone https://github.com/sourabhg07/flask-cicd-pipeline.git

cd flask-cicd-pipeline

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

python app.py
```

---

# 🐳 Docker

Build

```bash
docker build -t flask-cicd-pipeline .
```

Run

```bash
docker run -p 5000:5000 flask-cicd-pipeline
```

---

# 🧪 Run Tests

```bash
python -m pytest
```

---

# 🎯 CI Pipeline

Every push automatically:

✔ Install Dependencies

✔ Run Black

✔ Run Flake8

✔ Run Pytest

✔ Build Docker Image

---

# 👨‍💻 Author

**Sourabh Gupta**
