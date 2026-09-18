# Azure DevOps CI/CD Project

## Project Overview
End-to-end CI/CD pipeline using GitHub, Azure DevOps, Docker, and a self-hosted Windows agent.

## Architecture
GitHub
   ↓
Azure DevOps Pipelines
   ↓
Self-hosted Agent
   ↓
Docker Build
   ↓
Docker Image

## Technologies
- GitHub
- Azure DevOps
- Azure Pipelines
- Docker
- Linux/Windows
- YAML
- Git

## Pipeline
The pipeline automatically:
1. Pulls source code from GitHub
2. Runs on a self-hosted Azure DevOps agent
3. Builds the Docker image
4. Verifies the Docker build

## Result
Successfully implemented and tested an Azure DevOps CI/CD pipeline.
