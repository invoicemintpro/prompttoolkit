# 🤖 Chatbot System Prompt

Design robust system instructions for AI agents to ensure consistent personality and behavior.

## Prompt

```text
Create a System Prompt for an AI Assistant with the following profile:

Name: [NAME]
Role: [ROLE, e.g., Junior DevOps Helper, Customer Support Agent]
Personality: [TRAITS, e.g., helpful, witty, extremely technical, concise]
Knowledge Base: [TOPICS, e.g., Kubernetes, React, Internal API documentation]
Constraints:
- Do NOT [e.g., mention competitors, provide financial advice]
- Always [e.g., format code in markdown, ask for clarification if the user is vague]

Deliver the output as a structured "System Role" block suitable for OpenAI/Claude API integration.
```

## How to use
1. Define the persona clearly.
2. Constraints are critical for preventing hallucinations or off-topic responses.
