# ⚙️ API Generator Prompt

Rapidly scaffold REST or GraphQL APIs with best practices for routing, validation, and documentation.

## Prompt

```text
Act as a Backend Architect. Generate a [REST/GraphQL] API using [FRAMEWORK, e.g., Express, FastAPI, NestJS].

Requirements:
1. Endpoint: [ENDPOINT NAME, e.g., /users, /orders]
2. Purpose: [PURPOSE, e.g., CRUD operations, processing payments]
3. Data Schema: [DESCRIBE FIELDS, e.g., id, name, email, createdAt]
4. Authentication: [JWT/OAuth/None]

Deliverables:
- Controller logic.
- Data validation (e.g., Joi, Pydantic, Zod).
- Error handling middleware.
- Swagger/OpenAPI documentation snippet.
```

## How to use
1. Customize the bracketed fields with your specific requirements.
2. Specify your preferred validation library for better results.
