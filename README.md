# Federation Test with GitHub and Azure

This repository demonstrates the integration of GitHub with Azure services using federated credentials, specifically focusing on Azure Key Vault and Azure Container Registry (ACR).

## Overview

The `federation-test` repository showcases how to securely manage and deploy containerized applications by integrating GitHub Actions with Azure services. It utilizes federated credentials to streamline the authentication process between GitHub and Azure, enhancing security and efficiency.

## Key Features

- Integration of GitHub Actions with Azure Key Vault and ACR.
- Usage of Azure Federated Credentials for secure access.
- Example workflow for building and pushing Docker images to ACR.
- Demonstration of accessing secrets stored in Azure Key Vault.

## Getting Started

To understand how this integration works and to set up a similar workflow in your environment, refer to the detailed guide on my blog:

[GitHub Federated Integration with Azure Key Vault and ACR - Example](https://www.abrahamberg.com/blog/github-federated-integration-azure-key-vault-acr-example/)

This guide provides step-by-step instructions and explains the concepts behind Azure Federated Credentials, IAM roles in Azure, and secure handling of secrets.

## Repository Structure

- `Dockerfile`: The Dockerfile used for building the container image.
- `.github/workflows`: Contains the GitHub Actions workflow demonstrating the CI/CD pipeline.

