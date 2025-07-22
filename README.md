# 🧠 LLM Code Generator API

A FastAPI-powered backend application that leverages OpenAI's GPT-3.5 model to generate code from natural language prompts.

## 🚀 How it Works
- Accepts user prompts like: `"Write a Python function to reverse a string"`.
- Uses OpenAI API (`gpt-3.5-turbo`) to generate and return relevant code snippets.

## 🧪 Sample Prompt & Output
**Prompt:** `Write a Python function to reverse a string.`  
**Output:**  
```python
def reverse_string(s):
    return s[::-1]
