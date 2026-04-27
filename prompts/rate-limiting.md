# 🛑 API Rate Limiting Prompt

Design and implement fair and secure rate limiting strategies for your APIs.

## Prompt

```text
Act as a Backend Architect. Design a rate-limiting strategy for [API NAME/TYPE].

Requirements:
1. Algorithm selection (Token Bucket, Leaky Bucket, Fixed Window).
2. Limits for different tiers (e.g., Free vs Pro).
3. Storage for counters (e.g., Redis).
4. Response headers (X-RateLimit-Limit, X-RateLimit-Remaining).
5. Error response for 429 Too Many Requests.
```
