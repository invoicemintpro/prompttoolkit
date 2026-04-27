# 🔐 Auth & Security Validator Prompt

Review authentication logic and authorization flows for security gaps.

## Prompt

```text
Act as a Security Auditor. Review the following Authentication/Authorization logic.

Logic Description:
---
[DESCRIBE FLOW, e.g., JWT in cookies, RBAC with Middleware]
---

Analysis:
1. Is the JWT implementation secure (HttpOnly, SameSite, Secure flags)?
2. Check for privilege escalation risks.
3. Validate session expiration and revocation logic.
4. Suggest improvements for MFA or password hashing.
```
