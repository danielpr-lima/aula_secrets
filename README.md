# Aula Secrets

This repository is for learning about **GitHub Actions**, focusing on the use of **secrets**, **keys**, and **variables**.

## Overview

- A **Dockerfile** is set up to read environment variables from an `.env` file.
- When you **push to the `main` branch**, a GitHub Actions **deploy workflow** runs.
- During deployment, **secrets** are securely read and applied to the environment.

## How it works

1. **Add secrets** in your repository settings (`Settings > Secrets and variables > Actions`).
2. The workflow uses these secrets during deployment.
3. The Docker container is built and started with the environment variables.

## Usage

- Clone the repo and review the workflow and Dockerfile.
- Push changes to `main` to trigger the deploy workflow.
- Secrets are never exposed in logs or code.

## Notes

- Never commit sensitive data to the repository.
- Use GitHub secrets for all confidential information.

---
Happy learning!