# Day 2 – Prompts, Memory and Python for AI Agents

## Overview
Day 2 of the AI Agents Workshop focuses on writing effective prompts, managing conversation history, working with structured data, and learning essential Python concepts used in building AI agents.

The practical implementation involves creating a conversational AI chatbot for Sweet Crumbs Home Bakery using the Groq API.

## Topics Covered
- Understanding message roles: system, user, and assistant.
- Writing effective system prompts using Role, Facts, Rules, and Format.
- Few-shot prompting with example inputs and outputs.
- Understanding structured JSON responses.
- Managing conversation history and short-term memory.
- Working with Python dictionaries and JSON.
- Creating functions with parameters, return values, type hints, and docstrings.
- Understanding decorators in Python.
- Handling errors using try/except.

## Practical Implementation
- Installed and configured the OpenAI Python SDK.
- Connected to the Groq API using an API key stored in Google Colab Secrets.
- Generated responses using the GPT-OSS-120B model.
- Created a system prompt for the Sweet Crumbs Home Bakery assistant.
- Used Python dictionaries to store menu items, prices, and customer orders.
- Calculated order prices using reusable Python functions.
- Converted Python dictionaries into JSON strings and back.
- Implemented a decorator to log function calls and results.
- Maintained conversation history using a message list.
- Implemented a chatbot loop with conversation-history trimming.
- Handled API rate-limit and connection errors using try/except.

## Technologies Used
- Python
- Google Colab
- OpenAI Python SDK
- Groq API
- GPT-OSS-120B
- JSON

## Learning Outcomes
- Learned how to write effective system prompts.
- Understood how few-shot prompting improves response consistency.
- Learned how to work with structured data using dictionaries and JSON.
- Understood how conversation history helps an LLM maintain context.
- Learned to create reusable functions and decorators.
- Practised handling errors in Python applications.
- Built a basic AI-powered conversational chatbot for a bakery.
