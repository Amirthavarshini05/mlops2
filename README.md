# MLOps Lab - Complete Project Directory

This package contains project folders for all 15 MLOps Lab questions from the supplied model-question document.

## Folder naming

Each question is separated into folders such as:
- `1a`, `1b`
- `2a`, `2b`
- ...
- `14a`, `14b`, `14c`
- `15a`, `15b`, `15c`

For questions that have alternatives, all alternatives are included.

## Important placeholders

Replace these before real execution:
- `USERNAME`
- `YOUR_DOCKERHUB_USERNAME`
- `YOUR_EC2_PUBLIC_IP`
- `YOUR_KEY_PAIR_NAME`
- `YOUR_VALID_AMI_ID`
- AWS bucket names
- GitHub repository URLs
- Jenkins URL
- Kubernetes credentials

Cloud resources, Docker Hub, GitHub, Jenkins and AWS accounts are not created automatically by these files.

## Windows

Most Jenkins examples use Windows `bat` commands because the lab environment is commonly performed on Windows.

## Linux/Ubuntu

The Linux commands/configuration are included where the question specifically requires systemd, Nginx, Ansible or Terraform.

## Suggested order

1 -> 4: Git/Jenkins basics
5 -> 7: Docker/Jenkins/MLflow
8 -> 10: DVC/Blue-Green/Git/Docker
11 -> 13: FastAPI/GitHub Actions/Jenkins/Terraform
14 -> 15: Integrated CI/CD/Ansible/Kubernetes
