# Terraform: Up & Running (3rd Edition) - Code Examples

This repository contains code examples and infrastructure-as-code (IaC) configurations from the book **"Terraform: Up & Running: Writing Infrastructure as Code" (3rd Edition, 2024)** by Yevgeniy Brikman.

The examples demonstrate how to use Terraform to manage infrastructure across various cloud providers (primarily AWS) from the ground up—covering basic syntax, state management, modularization, loops, conditionals, production-grade deployment strategies, and testing.

## 🚀 Repository Structure

The repository is organized by chapters, following the progression of the book:

```text
.
├── README.md
├── ch01-why-terraform/             # Introduction to IaC and tool comparison
├── ch02-getting-started/           # Basic syntax, deploying a single server & cluster
│   ├── single-server/
│   ├── web-server/
│   └── web-server-cluster/
├── ch03-terraform-state/           # Managing state, shared state storage, and locking
│   ├── file-layout/
│   └── global/s3/
├── ch04-modules/                   # Creating reusable infrastructure components
│   ├── modules/
│   │   └── services/webserver-cluster/
│   └── stage/
│       └── services/webserver-cluster/
├── ch05-loops-conditionals/        # Advanced HCL: count, for_each, and conditionals
│   ├── live/
│   └── modules/
├── ch06-production-grade/          # Security, monitoring, and production practices
├── ch07-testing/                   # Unit testing, integration testing, and Terratest
└── ch08-team-workflow/             # CI/CD pipelines, styling, and multi-account setups