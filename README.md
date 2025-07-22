# Azure CI/CD Pipeline

This project deploys a simple HTML app to Azure App Service using GitHub Actions.

## 🚀 What It Does
- Deploys static HTML from `webapp/` to Azure App Service
- Triggered automatically on every `main` branch push

## 🧰 Tools Used
- GitHub Actions
- Azure App Service
- Azure CLI (for setup)

## ⚙️ Setup Instructions

1. Create an Azure Web App (Linux, HTML/static site)
2. Create an Azure service principal:
```bash
az ad sp create-for-rbac --name "gh-deploy" --sdk-auth