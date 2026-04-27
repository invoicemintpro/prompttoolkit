# 🧪 Unit Test Generator Prompt

Automatically generate comprehensive unit tests for your functions using your preferred testing framework.

## Prompt

```text
Act as a QA Engineer. Generate unit tests for the following [LANGUAGE] function using [TESTING FRAMEWORK, e.g., Jest, PyTest, Mocha].

Code:
---
[INSERT FUNCTION CODE HERE]
---

Requirements:
1. Cover happy path scenarios.
2. Include edge cases (null values, empty inputs, extreme ranges).
3. Mock external dependencies if necessary.
4. Ensure the tests follow best practices for readability and isolation.

Output the full test file code.
```

## How to use
1. Specify your language and framework.
2. Paste the function you want to test.
3. Perfect for ensuring high code coverage in new features.
