# Day 3 – First AI Agent Using LangChain

## Overview
Built a customer-support chatbot for **Sweet Crumbs Home Bakery** using LangChain and Groq LLM. The assistant answers customer questions about bakery products, prices, eggless cakes, and ordering policies.

## Features
- Answers customer queries about bakery products.
- Provides product prices and calculates order totals.
- Supports English and Telugu responses.
- Maintains conversation history.
- Uses prompt templates and output parsers.
- Tests chatbot responses using CSV test cases.
- Compares AI responses using different temperature settings.
- Demonstrates basic AI agent creation using LangChain.

## Technologies Used
- Python
- LangChain
- LangChain-Groq
- Groq API
- Google Colab
- CSV

## Language Model
- **Model:** `openai/gpt-oss-120b`
- **Provider:** Groq

## Bakery Information

| Product | Price |
|---|---:|
| Plum Cake | Rs 500 |
| Chocolate Cake | Rs 650 |
| Cupcakes | Rs 80 each |

- Orders require 24 hours' notice.
- Eggless versions are available for all cakes.

## LangChain Concepts Covered
- Chat Models (`ChatGroq`)
- Prompt Templates (`ChatPromptTemplate`)
- Conversation History (`MessagesPlaceholder`)
- Output Parsing (`StrOutputParser`)
- LangChain Chains
- Basic Agent Creation (`create_agent`)
- Response Testing and Evaluation

## Experiments
- Improved the system prompt and reran tests.
- Compared responses using different temperature settings.
- Classified business tasks into plain code, one LLM call, and an AI agent.
- Explored basic agent creation using LangChain.

## Setup and Execution

1. Open the project in Google Colab.
2. Install the required libraries:

```python
!pip install -q langchain langchain-groq
```

3. Add your `GROQ_API_KEY` to Google Colab Secrets.
4. Execute the Python code cells in order.
5. Create `tests.csv` with `question` and `must_include` columns.
6. Run `run_tests()` to evaluate the chatbot responses.

## Learning Outcomes
- Understanding the difference between chatbots and AI agents.
- Building LLM applications using LangChain.
- Managing conversation history.
- Creating and improving prompt templates.
- Testing and evaluating LLM responses.
- Understanding the fundamentals of AI agent architecture.

## Note
The current `create_agent()` implementation uses an empty tools list. It demonstrates basic agent setup; tool-based actions are not implemented in this project.
