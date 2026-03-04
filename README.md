# AWS Infrastructure Automation using Terraform with CI/CD

## Overview
Provisioned AWS infrastructure using Terraform and automated deployment using GitHub Actions.

## Infrastructure
- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Instance with Nginx

## CI/CD
Pipeline automatically runs:
- terraform init
- terraform plan
- terraform apply

## Security
- AWS credentials stored in GitHub Secrets
- AMI ID secured using environment variables