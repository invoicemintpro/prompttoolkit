# 💡 How to Use the AI Prompt Toolkit

This guide explains how to get the most out of these prompts.

## 1. Copy & Paste
The simplest way is to browse the `prompts/` directory, find the one you need, and copy the text inside the code blocks.

## 2. Customize Bracketed Fields
Most prompts contain placeholders like `[LANGUAGE]` or `[INSERT CODE HERE]`. For best results, replace these with your specific context.

### Example: Code Review
Instead of just asking "Review this code", use the template:
> "Act as a Senior Software Engineer with expertise in **React**. Review the following code for **performance bottlenecks**..."

## 3. Iteration (Chain of Thought)
If the first response isn't perfect, use follow-up prompts:
- "Can you expand on the second point?"
- "Show me a more secure way to implement that."
- "Reformat the output as a table."

## 4. Integration into Workflows
You can use these prompts as the basis for:
- **Git Hooks**: Automatically run the Code Review prompt on every commit.
- **SaaS Apps**: Use the API Generator or Invoice Generator logic as the underlying system prompt for your AI-powered product.
