# ☁️ Infrastructure as Code (IaC) Prompt

Generate optimized Terraform or CloudFormation scripts for cloud infrastructure.

## Prompt

```text
Act as a Cloud Engineer. Generate [Terraform/CloudFormation] scripts for the following infrastructure.

Cloud Provider: [AWS/GCP/Azure]
Infrastructure: [e.g., VPC with 2 public/private subnets, RDS instance, and S3 bucket]

Requirements:
1. Follow the principle of least privilege for IAM roles.
2. Include variables for environment-specific configurations.
3. Add outputs for critical resource IDs/endpoints.
4. Ensure the code is modular and reusable.
```
