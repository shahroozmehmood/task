# AWS Terraform Infrastructure

This repository contains Terraform scripts to provision an AWS infrastructure, including VPC, EC2 instances, RDS, S3, and CloudFront.

## Usage

To deploy the infrastructure, follow these steps:

1. Install Terraform.
2. Run `terraform init` to initialize the working directory.
3. Run `terraform plan` to view the resources that will be created.
4. Run `terraform apply` to provision the infrastructure.

## Components

- VPC with public and private subnets
- EC2 instances for Frontend SPA, Backend API, and microservices
- RDS MySQL database
- S3 bucket for media storage with CloudFront for CDN
