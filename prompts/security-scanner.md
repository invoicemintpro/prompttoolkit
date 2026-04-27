# 🛡️ Security Vulnerability Scanner Prompt

Identify potential security flaws and common vulnerabilities (OWASP) in your code snippets.

## Prompt

```text
Act as a Senior Security Researcher and Penetration Tester. Analyze the following code for security vulnerabilities.

Code:
---
[INSERT CODE HERE]
---

Analysis Checklist:
1. Injection flaws (SQLi, XSS, Command Injection).
2. Broken Authentication and Session Management.
3. Sensitive Data Exposure.
4. Insecure Direct Object References (IDOR).
5. Cross-Site Request Forgery (CSRF).

Deliverables:
- Vulnerability Report (Severity, Description, Impact).
- Proof of Concept (PoC) logic for exploitation (for educational purposes).
- Remediation steps and secure code snippets.
```
