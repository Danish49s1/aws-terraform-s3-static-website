# 🌐 Static Website Hosting on AWS using Terraform

This project deploys a **static food delivery website ("Fooding")** on **AWS S3** using **Terraform**.  
It automates the setup of an S3 bucket, configures it for static website hosting, uploads files, and applies public access policies.

---

## 🚀 Project Overview

- **Objective:** Host a static website on AWS using Infrastructure as Code (IaC)
- **Tools Used:** Terraform, AWS S3, IAM
- **Frontend:** HTML, CSS, JavaScript

---

## ⚙️ Features

- Automated creation of S3 bucket and website configuration  
- Public read permissions for all static content  
- Upload of `index.html` and supporting files  
- Outputs live S3 website endpoint after deployment  

---

## 🏗️ Terraform Configuration

Key resources:
- `aws_s3_bucket`
- `aws_s3_bucket_policy`
- `aws_s3_bucket_website_configuration`
- `aws_s3_object`

---

## 📦 Deployment Steps

1. Initialize Terraform  
   ```bash
   terraform init
2. Apply the configuration
     ```bash
   terraform apply -auto-approve
4. Get the website URL
   ```bash
   terraform output name
