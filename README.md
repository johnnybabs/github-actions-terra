# github-actions-terra
Repo for CloudBursts workflow 
[![Terraform CI/CD](https://github.com/johnnybabs/github-actions-terraform/actions/workflows/terraform.yml/badge.svg)](https://github.com/johnnybabs/github-actions-terraform/actions/workflows/terraform.yml)

This repository demonstrates GitHub Actions automation for Terraform deployments.

## Workflow

- **On Pull Request**: Runs format, validate, and plan
- **On Push to Main**: Runs format, validate, plan, and apply

## Resources Created

- S3 Bucket with versioning enabled. 

Nothing else done

Gave Jenkins access to this repo to trigger the pipeline
