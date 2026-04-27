# 📝 Git Commit Generator Prompt

Convert your "messy" changes into clean, atomic Conventional Commits.

## Prompt

```text
Act as a Senior Developer. Review these staged changes and write a clean, concise Git commit message following the Conventional Commits specification.

Diff/Changes Summary:
---
[INSERT GIT DIFF OR SUMMARY OF CHANGES]
---

Format:
- Type: [feat, fix, docs, style, refactor, test, chore]
- Scope: [optional]
- Description: Concise imperative summary.
- Body: [optional] detailed explanation if necessary.
```
