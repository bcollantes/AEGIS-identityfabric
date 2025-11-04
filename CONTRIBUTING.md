# Contributing Guidelines

## How to contribute
- Open a GitHub Issue for proposals, bugs or questions.
- Fork and create a feature branch from `main`.
- Keep PRs small, atomic and well-described.

## Coding
- Use IaC (Terraform/CloudFormation/ARM) for infra changes.
- Enforce Policy-as-Code (OPA/Rego, Sentinel) for critical changes.
- Security-first: no static secrets; use short-lived tokens.

## Docs
- Markdown (EN preferred) + Spanish translation when possible.
- Diagrams in ASCII and `.drawio` when available.

## Commit messages
- Conventional Commits recommended: feat:, fix:, docs:, refactor:, test:, chore:
