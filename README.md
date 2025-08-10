CI/CD Node.js Sample

This is a minimal Node.js app with a GitHub Actions CI/CD workflow that builds a Docker image and pushes it to Docker Hub.

Files
server.js - simple Express server
package.json - project manifest
Dockerfile - Docker image definition
.github/workflows/main.yml - GitHub Actions workflow


How to use
Create a Docker Hub access token.
Add DOCKERHUB_USERNAME and DOCKERHUB_TOKEN to your repo secrets.
Push to the main branch to trigger the workflow.
