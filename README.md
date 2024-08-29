# AWS Service Catalog using reusable Github Actions

This repository contains the reusable Github Actions workflow for:
1. Provisioning AWS ServiceCatalog (SC) Portfolio 
2. Provisioning SC Product
3. Adding Launch Contraint
4. Portfolio Product Association
5. Portfolio Principal Association

The main workflow at `.github/workflows/workflow.yaml` has the `trigger` as `workflow_call`, which makes it possible to call this workflow from any other workflow. 
For more detail please refer [Events that trigger workflows](https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows)

## Table of content
- [AWS Service Catalog using reusable Github Actions](#aws-service-catalog-using-reusable-github-actions)
  - [Table of content](#table-of-content)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
  - [Architecture](#architecture)
  - [How to Use](#how-to-use)
  - [Best practices](#best-practices)
  - [Limitations](#limitations)
  - [Contributing](#security)
  - [License](#license)
  - [Contributors](#contributors)
 
  
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

