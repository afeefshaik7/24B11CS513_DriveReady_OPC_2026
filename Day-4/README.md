# Day 4 – Tools, Structured Output and Google Sheets

## About
This project demonstrates building an AI agent using **LangChain and Groq**. The agent uses custom Python tools to check prices, retrieve opening hours, and manage customer orders. It uses Pydantic for data validation and Google Sheets to store confirmed orders.

## Features
- AI agent with custom tool calling.
- Price calculation and opening hours checking.
- Customer order management.
- Structured data validation using Pydantic.
- Automatic order storage in Google Sheets.
- Conversation history management.
- English and Telugu responses.
- Basic error handling and API retries.

## Technologies Used
- Python
- LangChain
- Groq LLM (`openai/gpt-oss-20b`)
- Pydantic
- Google Sheets
- GSpread
- Google Colab

## Custom Tools
- `get_price()` – Calculates the total price based on item and quantity.
- `is_open()` – Checks bakery opening hours.
- `log_order()` – Validates and saves customer orders to Google Sheets.

## Setup and Execution

1. Open the project in Google Colab.
2. Install the required packages:

```python
!pip install -q langchain langchain-groq gspread
```

3. Add your Groq API key to Google Colab Secrets as `GROQ_API_KEY`.
4. Execute the code cells in order.
5. Authenticate your Google account when prompted.
6. Start interacting with the AI agent.

**Note:** The first execution creates a Google Spreadsheet named `Sweet Crumbs Orders`. For subsequent executions, open the existing spreadsheet using `gc.open()` instead of creating another one. Avoid appending the header row again.

## Outcome
Developed an AI agent capable of performing tasks using custom tools, validating structured order data, maintaining conversation history, and automatically storing customer orders in Google Sheets.
