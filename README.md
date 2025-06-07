# DevSecOps Pipeline 

## 🎯 Project Goal

This project demonstrates a simple DevSecOps pipeline for a Python (Flask) web application covering the following stages:

- Building a Docker image  
- Static code analysis using Semgrep  
- Container vulnerability scanning with Trivy  
- Dynamic application security testing (DAST) with OWASP ZAP  
- Automated execution using GitLab CI

## 🛠️ Tools Used

- Python Flask (simple web app)  
- Docker  
- GitLab CI  
- Semgrep (Static Application Security Testing)  
- Trivy (Container Vulnerability Scanner)  
- OWASP ZAP (Dynamic Application Security Testing)

## 🚀 How to Run

### Locally:

```bash
# Build Docker image
docker build -t devsecops-app .

# Run container
docker run -p 5000:5000 devsecops-app
