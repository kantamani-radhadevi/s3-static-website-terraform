# AWS Static Website Hosting using Terraform

## Project Overview
This project demonstrates how to host a static website on Amazon S3 using Terraform (Infrastructure as Code).

## Objective
To create an S3 bucket, enable static website hosting, upload an HTML webpage, and make the website publicly accessible.

## Technologies Used
- AWS S3
- Terraform
- HTML
- Git & GitHub
- Ubuntu

## Project Structure

```text
s3-static-website/
├── main.tf
├── index.html
├── .gitignore
├── .terraform.lock.hcl
└── README.md
```

## Implementation Steps

1. Configured the AWS provider using Terraform.
2. Created an Amazon S3 bucket.
3. Enabled static website hosting.
4. Configured public access using an S3 bucket policy.
5. Created an `index.html` webpage.
6. Uploaded the HTML file to the S3 bucket using Terraform.
7. Deployed the infrastructure using `terraform init`, `terraform plan`, and `terraform apply`.
8. Accessed and tested the website using the S3 website endpoint.

## Website Preview

The website displays:

**Welcome to My Website!**

This website is hosted on Amazon S3 using Terraform.

## How to Run

1. Configure AWS credentials.
2. Initialize Terraform:

   `terraform init`

3. Validate the configuration:

   `terraform validate`

4. Preview the infrastructure:

   `terraform plan`

5. Deploy the resources:

   `terraform apply`

6. Open the website URL displayed by Terraform.

## Learning Outcomes

- Understanding Infrastructure as Code.
- Creating and managing AWS S3 resources using Terraform.
- Configuring static website hosting.
- Managing public access through bucket policies.
- Deploying infrastructure and hosting a website on AWS.

## Author
Kantamani Radhadevi
