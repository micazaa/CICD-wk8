# CICD-wk8

![CI Status](https://github.com/micazaa/CICD-wk8/actions/workflows/main.yml/badge.svg)

## Project Overview

This project demonstrates a complete CI/CD pipeline using GitHub Actions.

## Technologies Used

- GitHub Actions
- Node.js
- GitHub Pages

## Pipeline Process

1. Push code to the main branch.
2. GitHub Actions automatically starts.
3. The repository is checked out.
4. Node.js is installed.
5. Dependencies are installed.
6. Tests are executed.
7. Deployment to GitHub Pages is performed.

## Deployment Trigger

The deployment is triggered automatically whenever code is pushed to the `main` branch.

## Security

Sensitive information is stored using GitHub Secrets (for example, `API_KEY`). Credentials are never hardcoded in the workflow or source code.

## Live Website

https://micazaa.github.io/CICD-wk8/