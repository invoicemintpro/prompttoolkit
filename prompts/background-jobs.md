# 👷 Background Job Worker Prompt

Design reliable background processing for long-running tasks like email sending or image processing.

## Prompt

```text
Act as a Distributed Systems Engineer. Design a background job worker for [TASK, e.g., Batch image resizing].

Toolbox: [e.g., Sidekiq, Celery, BullMQ, RabbitMQ]

Deliverables:
1. Job structure and payload.
2. Retry strategy and Exponential Backoff configuration.
3. Dead Letter Queue (DLQ) handling.
4. Monitoring and alerting for job failures.
5. Provide a sample worker and producer implementation.
```
