# 🔗 CI/CD Pipeline Builder Prompt

Design automated build, test, and deployment pipelines using GitHub Actions or GitLab CI.

## Prompt

```text
Act as a DevOps Architect. Generate a [GitHub Actions/GitLab CI] yaml file for [APP STACK].

Pipeline Stages:
1. Build & Lint.
2. Unit & Integration Tests.
3. Security Scan (SAST).
4. Containerize (Docker).
5. Deploy to [STAGING/PRODUCTION].

Ensure the pipeline uses caching for dependencies and secrets management for sensitive keys.
```
