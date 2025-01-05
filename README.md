# ML-model-deploy-azure-ACR-app_service
🌟 README.md

Prerequisites

Azure CLI installed locally. 💻

Terraform CLI installed. 🛠️

Azure Resource Manager (ARM) credentials stored in GitHub Secrets as AZURE_CREDENTIALS. 🔐

Setup Instructions

Clone the repository. 📂

Navigate to the project-folder/terraform directory. 📂

Initialize Terraform:

terraform init

Apply Terraform configuration:

terraform apply

Use GitHub Actions workflow to automate build and deployment. 🤖

Folder Structure

app/: Application code. 💻

Dockerfile: Defines the container build process. 🐳

terraform/: Contains infrastructure setup for Azure. 🌐

.github/workflows/: CI/CD workflow configuration. 🔄

