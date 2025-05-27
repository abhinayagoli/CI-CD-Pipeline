# Node.js Demo App with CI/CD

This is a simple Node.js web app with an automated CI/CD pipeline using GitHub Actions and Docker.

## Setup

- Node.js app (Express)
- Dockerfile for containerization
- GitHub Actions workflow for CI/CD

## Workflow

1. On push to `main`:
   - Installs dependencies
   - Runs tests
   - Builds Docker image
   - Pushes image to DockerHub

## Secrets Required in GitHub Repo

- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`