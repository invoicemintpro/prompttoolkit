# 🐳 Dockerfile Generator Prompt

Generate optimized, production-ready Dockerfiles for any tech stack.

## Prompt

```text
Act as a DevOps Engineer. Generate a Dockerfile for a [LANGUAGE/FRAMEWORK] application.

Project Structure:
- Entry point: [e.g., app.py, index.js, main.go]
- Dependencies file: [e.g., requirements.txt, package.json]
- Port: [e.g., 8080]

Requirements:
1. Use a slim/minimal base image.
2. Implement multi-stage builds (if applicable) for smaller image size.
3. Follow security best practices (non-root user, minimal layers).
4. Include a basic .dockerignore file.
```
