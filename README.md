# NGINX Demo

This repository demonstrates how to deploy an NGINX application using GitHub Actions and Docker Compose.

## Deployment

1. Push changes to the `main` branch.
2. GitHub Actions will handle the deployment to the remote server.

## Configuration

- **Environment Variable**: The target server IP is configurable via the `SERVER_IP` environment variable in the workflow.
- **Secrets**: Ensure that `SSH_PRIVATE_KEY` is configured in the GitHub repository secrets.
