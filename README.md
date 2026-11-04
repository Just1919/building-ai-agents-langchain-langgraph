# Building AI Agents with LangChain & LangGraph

**From LLM Fundamentals to Production-Ready Multi-Agent Systems**

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![LangChain](https://img.shields.io/badge/LangChain-Framework-green)
![LangGraph](https://img.shields.io/badge/LangGraph-Agentic_Workflows-orange)
![Technical Series](https://img.shields.io/badge/Technical_Series-7_Articles-purple)

## Overview

Artificial Intelligence is evolving beyond simple interactions with Large Language Models (LLMs).

Modern AI applications increasingly rely on autonomous agents capable of using tools, retrieving information, managing state, collaborating with other agents, and executing complex workflows.

This repository accompanies a **7-part technical article series** dedicated to building practical AI agents with **LangChain and LangGraph**.

The objective is to explore the concepts, implementation patterns, architectures, and engineering practices required to move from basic LLM applications to more advanced and production-oriented agentic systems.

Each article combines technical explanations, Python implementations, practical examples, and architectural insights.

## Learning Roadmap

### 01 — Introduction & LangChain Fundamentals
Understanding the foundations of LLM-powered applications.

Topics:
- Large Language Models (LLMs)
- Chat models and prompt templates
- Chains and LangChain Expression Language (LCEL)
- Runnables and application composition

[Explore Part 01](./01-langchain-fundamentals/)

### 02 — Memory & Vector Databases
Understanding how AI applications retrieve and manage contextual information.

Topics:
- Embeddings
- Vector databases
- Semantic search
- Retrieval-Augmented Generation (RAG)
- Conversational memory

[Explore Part 02](./02-memory-and-vector-databases/)

### 03 — AI Agents & Tools
Building agents capable of interacting with external tools and executing actions.

Topics:
- AI agents
- Custom tools
- Tool calling and function calling
- Agent execution and control

[Explore Part 03](./03-ai-agents-and-tools/)

### 04 — LangGraph Workflows
Designing structured, stateful agent workflows.

Topics:
- Graph-based architectures
- State management
- Nodes and edges
- Conditional routing
- LangChain vs. LangGraph

[Explore Part 04](./04-langgraph-workflows/)

### 05 — Multi-Agent Systems & Real-World Applications
Building collaborative systems with specialized agents.

Topics:
- Multi-agent architectures
- Agent collaboration
- Researcher, Writer and Reviewer agents
- Workflow orchestration
- Practical applications

[Explore Part 05](./05-multi-agent-systems/)

### 06 — Memory, Feedback & Human-in-the-Loop
Improving reliability through persistent state and human supervision.

Topics:
- Persistent memory
- Feedback loops
- Human-in-the-loop
- Human approval and validation
- Agent reliability

[Explore Part 06](./06-memory-feedback-human-in-the-loop/)

### 07 — Production, Integration & Optimization
Moving from prototypes to deployable AI applications.

Topics:
- FastAPI integration
- Docker
- Database integration
- Deployment
- Debugging and monitoring
- Security and optimization

[Explore Part 07](./07-production-integration-optimization/)

## Tech Stack

- **Programming:** Python
- **LLM Frameworks:** LangChain, LangGraph
- **AI & NLP:** LLMs, embeddings, prompt engineering
- **Retrieval:** Vector databases, semantic search, RAG
- **Agentic AI:** Tool calling, multi-agent orchestration, state management
- **Backend:** FastAPI
- **Deployment:** Docker

Additional tools and technologies may be introduced throughout the series.

## Getting Started

### Clone the repository

```bash
git clone https://github.com/Just1919/building-ai-agents-langchain-langgraph.git

cd building-ai-agents-langchain-langgraph
```

### Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows:**
```bash
.venv\Scripts\activate
```

**Linux/macOS:**
```bash
source .venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

Create a `.env` file using `.env.example` as a reference and provide the required API credentials.

Never commit API keys or sensitive credentials.

## Articles & Publications

The seven articles will be published progressively on Medium.

Follow the series:

- **Medium:** [Justin Djakas](https://medium.com/@justindjakas)
- **LinkedIn:** [Justin Djakas](https://linkedin.com/in/yawo-justin-djakas)
- **GitHub:** [Just1919](https://github.com/Just1919)

Individual article links will be added as they become available.

## Contributions & Feedback

Suggestions, discussions, and feedback are welcome.

If you find this repository useful, consider giving it a ⭐.

## License

This project is licensed under the MIT License.

---

**Let's move beyond simple LLM interactions and build useful, reliable AI agents.**
