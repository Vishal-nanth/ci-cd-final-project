# CI/CD Final Project

This project demonstrates a CI/CD pipeline using GitHub Actions and Tekton on OpenShift.

## Features
- Linting using flake8
- Unit testing using nose
- Tekton pipeline integration
- OpenShift deployment

## How it works
1. Code is pushed to GitHub
2. GitHub Actions runs lint and tests
3. Tekton pipeline executes tasks
4. Application is deployed on OpenShift