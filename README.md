# AI Stock Analysis Assistant

An AI-powered stock analysis backend built using FastAPI and an agent-based LLM architecture.

## Features
- LLM agent with tool calling
- Real-time financial data integration
- Streaming responses
- Modular backend architecture

## Tech Stack
- Python
- FastAPI
- LangChain
- OpenAI
- yfinance
- Uvicorn

## Run Locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload