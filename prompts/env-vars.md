# 🔐 Environment Variables Best Practices Prompt

Manage secrets and configuration safely using environment variables and secret managers.

## Prompt

```text
Act as a Security Architect. Review my approach for managing environment variables in a [e.g., Docker/Kubernetes/Serverless] environment.

Approach:
---
[DESCRIBE APPROACH]
---

Analysis:
1. Are secrets being leaked in logs or image layers?
2. Suggest a strategy for local vs production configuration.
3. Recommend a Secret Manager (e.g., AWS Secrets Manager, HashiCorp Vault).
4. Provide a template for a secure .env.example file.
```
