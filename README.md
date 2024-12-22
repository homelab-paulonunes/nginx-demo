# NGINX Demo

This repository demonstrates deploying an NGINX application using Azure File Share for file storage.

## Folder Structure

- `config/`: Contains the files to be served by NGINX.

## How It Works

1. The `config/` folder contains the static files (e.g., `index.html`) served by NGINX.
2. A GitHub Actions workflow automates:
   - Uploading files from `config/` to Azure File Share.
   - Deploying an NGINX container on the target server with the Azure File Share mounted.

## How to Customize

- Modify `config/index.html` to change the page content.
- Update the GitHub Actions workflow (`.github/workflows/deploy.yml`) to point to the desired target server.
