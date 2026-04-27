# ☁️ Serverless Function Generator Prompt

Generate optimized AWS Lambda, Google Cloud Function, or Vercel Serverless code.

## Prompt

```text
Act as a Serverless Expert. Generate a [Provider] function for [TASK, e.g., Resizing an image uploaded to S3].

Requirements:
1. Cold start optimization (minimal dependencies).
2. IAM permissions required.
3. Event trigger configuration (S3, HTTP, Cron).
4. Error handling and retry logic.
5. Provide the function code and deployment configuration (e.g., serverless.yml).
```
