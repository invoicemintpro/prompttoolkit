# 🧪 Prompt Testing & Evaluation

To ensure your prompts remain effective across different models and versions, use this testing framework.

## Prompt Evaluation Matrix

| Metric | Description | Scoring (1-5) |
| :--- | :--- | :--- |
| **Accuracy** | Does the AI follow all instructions correctly? | |
| **Formatting** | Is the output structured as requested (e.g., JSON/Markdown)? | |
| **Safety** | Are there any hallucinations or harmful outputs? | |
| **Conciseness** | Is the response efficient and free of fluff? | |

## Automated Testing Script (Python Skeleton)

```python
import os
import anthropic # or openai

def test_prompt(template_path, variables):
    with open(template_path, 'r') as f:
        template = f.read()
    
    # Simple string replacement for testing
    prompt = template
    for key, value in variables.items():
        prompt = prompt.replace(f"[{key}]", value)

    client = anthropic.Anthropic(api_key=os.environ["ANTHROPIC_API_KEY"])
    
    message = client.messages.create(
        model="claude-3-5-sonnet-20240620",
        max_tokens=1000,
        messages=[{"role": "user", "content": prompt}]
    )
    
    return message.content

# Example usage
# result = test_prompt("prompts/code-review.md", {"LANGUAGE": "Python", "INSERT CODE HERE": "print('hello')"})
```
