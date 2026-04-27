# 🔍 SQL Query Generator Prompt

Translate natural language into complex, optimized SQL queries.

## Prompt

```text
Act as a SQL Expert. Convert this natural language request into a high-performance SQL query.

Database Schema Context:
---
[DESCRIBE TABLES, e.g., Users(id, name), Orders(id, user_id, total, date)]
---

Request:
"[INSERT REQUEST, e.g., Find the top 5 users who spent the most in the last 30 days]"

Output:
- Optimized SQL query.
- Brief explanation of the logic (joins, aggregations, filters).
```
