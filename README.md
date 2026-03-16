# Cloud Resume Challenge

A cloud-hosted resume built on AWS as part of the [Cloud Resume Challenge](https://cloudresumechallenge.dev/).

## Architecture

- **S3** — Static website hosting
- **CloudFront** — CDN and HTTPS enforcement
- **ACM** — SSL/TLS certificate
- **Route 53** — DNS management
- **API Gateway + Lambda + DynamoDB** — Serverless visitor counter (coming soon)
- **Terraform** — Infrastructure as Code (coming soon)
- **GitHub Actions** — CI/CD pipeline

## Stack

- HTML/CSS (no frameworks)
- Python (Lambda)
- Terraform
- AWS CLI

## Live Site

[nicholasmadson.dev](https://nicholasmadson.dev)
