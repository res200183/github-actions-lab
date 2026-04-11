# GitHub Actions to AWS S3 Demo

This repository demonstrates a simple CI workflow using GitHub Actions and AWS S3.

## Project goal
The purpose of this project is to show a practical GitHub Actions pipeline that:

- runs automatically on `git push`
- executes on a GitHub-hosted runner
- creates a file during the workflow
- authenticates to AWS using GitHub Secrets
- uploads the generated file to Amazon S3

## Workflow summary
The pipeline performs the following steps:

1. Checks out the repository
2. Creates a build file
3. Configures AWS credentials securely from GitHub Secrets
4. Uploads the file to an S3 bucket

## Technologies used
- Git
- GitHub
- GitHub Actions
- YAML
- AWS S3
- AWS CLI

## Repository structure
```text
.github/
  workflows/
    ci.yml

