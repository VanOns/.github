# .github

This repository contains default community health files and workflow templates for the organization.

## Workflow Templates

These templates are available for use in repositories across the organization.

### Development Deployment

- **File**: `workflow-templates/development-deploy.yml`
- **Description**: Deploys a Laravel application to our development cluster.
- **Trigger**: Manual (`workflow_dispatch`)
- **Key Features**:
  - Sets up SSH keys
  - Configures `kubectl`
  - Sets up WireGuard VPN
  - Configures Node.js and PHP environments
  - Intended for Laravel applications

#### Usage

To use this workflow in your repository:

1. Navigate to the **Actions** tab in your repository.
2. Click **New workflow**.
3. Look for "Development Deployment" under the organization's workflows.
4. Set up the required secrets (`DEV_APP_NAME`).
