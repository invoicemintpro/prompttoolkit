# 🐞 Bug Fixer Prompt

Use this prompt to diagnose and fix tricky bugs by providing the error context and relevant code.

## Prompt

```text
You are an expert debugger. I am encountering an issue in my [LANGUAGE/ENVIRONMENT] application.

Error Message/Behavior:
---
[INSERT ERROR OR DESCRIBE BUG HERE]
---

Relevant Code:
---
[INSERT CODE SNIPPET HERE]
---

Task:
1. Explain why this error is occurring.
2. Provide a corrected version of the code.
3. Suggest a unit test to prevent this bug from reoccurring.
```

## How to use
1. Fill in the environment (e.g., Node.js, Browser, AWS Lambda).
2. Paste the exact error message or a detailed description of the bug.
3. Include the code block where you suspect the bug resides.
