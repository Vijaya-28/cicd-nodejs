# CI/CD Node.js Sample

This is a minimal Node.js app with a GitHub Actions CI/CD workflow that builds a Docker image and pushes it to Docker Hub.

## Files
- server.js - simple Express server
- package.json - project manifest
- Dockerfile - Docker image definition
- .github/workflows/main.yml - GitHub Actions workflow

## How to use
1. Create a Docker Hub access token.
2. Add `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN` to your repo secrets.
3. Push to the `main` branch to trigger the workflow.
