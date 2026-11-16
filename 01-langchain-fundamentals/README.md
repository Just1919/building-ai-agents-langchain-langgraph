# Part 1 — Introduction & LangChain Fundamentals

Code companion for the first article of the series
**Building AI Agents with LangChain & LangGraph**.

📖 **Read the article on Medium:** [Part 1 — Introduction & LangChain Fundamentals](#)

## What you will learn

- What an LLM application is made of (prompt, model, memory, tools)
- Prompt templates, chains, and output parsers
- The LangChain Expression Language (LCEL) and the pipe operator `|`
- Runnables: `invoke`, `batch`, `stream`, `ainvoke`
- Structured output with Pydantic
- Parallel composition with `RunnableParallel` and custom logic with `RunnableLambda`
- Retries, fallbacks, and input validation
- Tracing with LangSmith
- A mini project: a content analyzer

## Prerequisites

- Python 3.12 (3.10+ should work)
- An OpenAI API key
- (Optional) A LangSmith API key for tracing

## Setup

```bash
# From the repository root
python3 -m venv .venv-agentic-ai
source .venv-agentic-ai/bin/activate    # Windows: .venv-agentic-ai\Scripts\activate

cd 01-langchain-fundamentals
python -m pip install -U -r requirements.txt
python -m pip install jupyter ipykernel
```

Create your environment file:

```bash
cp .env.example .env
```

Then edit `.env` and add your keys. **Never commit `.env`.**

## Run the notebook

```bash
jupyter notebook 01_langchain_fundamentals.ipynb
```

Or open it directly in VS Code and select the `.venv-agentic-ai` kernel.

## Notebook contents

The notebook follows the structure of the article:

1. Direct API call without LangChain
2. Environment setup and installation check
3. First chain: prompt → model → parser
4. Prompt patterns (system/human messages, multiple variables, Q&A)
5. Structured output with Pydantic
6. Multi-step chains, `RunnableParallel`, `RunnableLambda`
7. Runnables: `invoke`, `batch`, `stream`, `ainvoke`
8. Swapping models with `init_chat_model`
9. Error handling: retries, fallbacks, validation
10. Tracing with LangSmith
11. Mini project: content analyzer

## Verify your installation

```bash
python -c "from importlib.metadata import version; [print(p, version(p)) for p in ['langchain','langchain-core','langchain-openai','langgraph','langsmith']]"
```

`langchain` and `langgraph` should be on version 1.x.

## Notes

- This series targets **LangChain 1.x** and **LangGraph 1.x**. Many older tutorials use deprecated patterns (`LLMChain`, `ConversationBufferMemory`, `initialize_agent`) that are not used here.
- Some reasoning models do not support the `temperature` parameter. If you switch models and get an error, remove it.
- Running the notebook calls the OpenAI API and may incur small costs.
- Clear sensitive outputs before committing the notebook.

## The series

1. **Introduction & LangChain Fundamentals** ← you are here
2. Memory & Vector Databases
3. AI Agents & Tools
4. LangGraph Workflows
5. Multi-Agent Systems & Real-World Applications
6. Memory, Feedback & Human-in-the-Loop
7. Production, Integration & Optimization

## Connect

- LinkedIn:https://linkedin.com/in/yawo-justin-djakas
- Medium: https://medium.com/@justindjakas
- GitHub: [JUST1919](https://github.com/JUST1919)
