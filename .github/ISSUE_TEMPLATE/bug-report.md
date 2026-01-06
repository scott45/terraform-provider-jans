---
name: Bug Report
about: Report a bug or unexpected behavior in the Terraform provider
title: "[BUG] "
labels: bug
assignees: ''
---

## Bug Report

### Description

Provide a clear and concise description of the bug (e.g., unexpected error during plan/apply, incorrect resource state, provider crash).

### Terraform Configuration
````hcl
# Paste your relevant Terraform configuration here (provider block + affected resources)
# Remove any sensitive values (URLs, tokens, secrets) before posting!
````

### Expected Behavior

What did you expect to happen?

### Actual Behavior

What actually happened? Include error messages or logs.

### Steps to Reproduce

1. Run `terraform init`
2. Run `terraform plan` or `terraform apply`
3. Observe error

### Environment

- **Provider Version**: (e.g., v0.1.0)
- **Janssen Server Version**: (e.g., v1.2.0)
- **Terraform Version**: (e.g., v1.9.0)
- **OS**: (e.g., Linux, macOS)

### Logs/Screenshots

Attach relevant logs (set `TF_LOG=DEBUG` for verbose output) or screenshots.

### Additional Context

Any other information that might help diagnose the issue.