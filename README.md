# Hosting-a-static-website-on-S3
This repository contains the Terraform infrastructure and GitHub Actions workflow to host a static site on AWS S3 + CloudFront.

## Setup
1. Install [Terraform](https://www.terraform.io/).
2. Add your AWS credentials to GitHub Secrets: `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`.
3. Run `terraform init` and `terraform apply` in the `/terraform` folder.
4. Push your changes to the `main` branch to trigger the deployment.

