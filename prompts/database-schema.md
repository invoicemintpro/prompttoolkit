# 🗄️ Database Schema Generator Prompt

Generate optimized SQL or NoSQL database schemas for any application requirement.

## Prompt

```text
Act as a Senior Database Administrator. Design a [Relational/NoSQL] database schema for [APP DESCRIPTION].

Core Entities & Relationships:
- [ENTITY 1, e.g., Users]
- [ENTITY 2, e.g., Projects]
- [ENTITY 3, e.g., Tasks]

Requirements:
1. Ensure normalization (if SQL) or optimized access patterns (if NoSQL).
2. Include indexes for high-performance queries.
3. Provide the DDL (Data Definition Language) or JSON schema.
```

## How to use
1. List your primary models/entities.
2. Specify if you prefer SQL (PostgreSQL, MySQL) or NoSQL (MongoDB, DynamoDB).
