#  Static Website Hosting on AWS using Terraform

##  Project Overview

This project demonstrates how to host a static website using Amazon S3 and deliver it globally using Amazon CloudFront. The entire infrastructure is automated using Terraform.

##  Tech Stack

* AWS S3 (Static Website Hosting)
* AWS CloudFront (CDN)
* Terraform (Infrastructure as Code)

##  Features

* Static website hosted on S3
* Global content delivery using CloudFront
* HTTPS enabled via CloudFront
* Infrastructure fully automated using Terraform
* Optimized cost using CloudFront Price Class

##  Project Structure

```
.
├── main.tf
├── variables.tf
├── outputs.tf
├── provider.tf
├── www/
│   └── index.html
```

##  Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/s3-cloudfront-static-website.git
cd s3-cloudfront-static-website
```

### 2. Initialize Terraform

```bash
terraform init
```

### 3. Apply Terraform

```bash
terraform apply
```

##   Output

* S3 Website URL - s3://my-demo-bucket-s31210/index.html
* CloudFront Distribution URL - d3cpascj1zlak0.cloudfront.net

 ## Improvements (Future Scope)

* Add custom domain using Route53
* Secure S3 using Origin Access Identity (OAI)
* CI/CD pipeline using GitHub Actions

 Demo

<img width="2535" height="1358" alt="image" src="https://github.com/user-attachments/assets/fa9b9cd8-5ecc-4216-b4fa-729f39964899" />


##  Author

Sivaganesh T


Your Name
