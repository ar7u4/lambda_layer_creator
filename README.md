Python AWS Lambda Builder

# AWS Lambda Layer Build Workflow

This GitHub Actions workflow automates the process of building a Lambda layer with Python dependencies for AWS Lambda. 
It uses an Amazon Linux 2 service container to ensure compatibility with the Lambda execution environment.

## Workflow Overview

- **Trigger:** Automatically triggered on pushes to the `main` branch.
- **Jobs:**
  - `build`: Runs on the latest Ubuntu environment.
    - Sets up a Python environment based on the specified versions.
    - Installs dependencies from `requirements.txt` and organizes folder structure.
    - Packages Lambda layer and uploads as an artifact.

## Workflow Details


