# AWS Lambda CI/CD Pipeline

This repository, [iac23/lambdap-cicd](https://github.com/iac23/lambdap-cicd), contains an AWS Lambda function deployment setup with a CI/CD pipeline for automated testing and deployment.

## Project Overview
The goal of this project is to demonstrate a CI/CD pipeline for AWS Lambda functions, enabling automated building, testing, and deployment to AWS. It showcases the use of infrastructure as code and continuous integration/continuous deployment practices to streamline Lambda function updates.

## Structure
- `lambda/`: Contains the AWS Lambda function code (e.g., Node.js, Python, or Java files).
  - Example: `index.js` or `handler.py` for the Lambda logic.
- `.github/workflows/`: Houses CI/CD workflow files (e.g., `deploy.yml`) using GitHub Actions for automation.
  - Example: Triggers on push to deploy to AWS Lambda.
- `terraform/`: Includes Terraform configurations for AWS infrastructure (e.g., IAM roles, Lambda function resources).
  - Examples: `main.tf`, `variables.tf`, `outputs.tf`.
- `.gitignore`: Ignores build artifacts, dependencies, and Terraform state files (e.g., `node_modules/`, `.terraform/`, `terraform.tfstate`).
