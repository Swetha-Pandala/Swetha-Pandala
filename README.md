<h1 align="center">Hi, I'm Swetha Pandala 👋</h1>

<p align="center">
  <b>Applied AI Engineer · Agentic AI · Full-Stack & Backend</b><br/>
  I build AI agents that do real work in production, and the Python services and React apps around them.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
</p>

---

## About me

I'm a software engineer with about 7 years of hands-on experience across financial services and healthcare, at companies including **MetLife**, **Morgan Stanley**, and **Optum**. For the last few years my focus has been Generative AI and agentic systems, built for regulated environments where answers have to be correct, traceable, and private.

My day-to-day work is the unglamorous part that makes agents reliable:

- **Agent harnesses:** planner, retriever, validator, and executor agents with shared state, tool calling, memory, and human-in-the-loop checkpoints
- **Tools:** Model Context Protocol (MCP) interfaces so agents can safely call real APIs, databases, and document services
- **Retrieval:** RAG pipelines with chunking, hybrid search, reranking, metadata filters, and citations users can check
- **Evals:** regression test sets, LLM-as-judge scoring, and latency, token, and cost tracking on every prompt or model change
- **Production:** FastAPI streaming services, async workers, guardrails, PII handling, Docker, Kubernetes, and CI/CD

Outside work, I'm an AI enthusiast at heart. I read new papers and repos every week, try new agent frameworks as soon as they land, and I'm pursuing a **Doctorate in Business Administration with Applied AI** to understand how AI changes how companies actually work.

## Featured projects

### 🧠 [Multi-Agent Financial Intelligence Platform](https://github.com/Swetha-Pandala/fin-mind-weave)
A full-stack agentic AI app for financial analysis. A supervisor classifies each question into one of 8 intents and routes it through only the agents it needs: retrieval, transaction analysis, risk and compliance, and report writing.

- **Grounding contract:** the writer can only cite what the retriever returned, and declines instead of guessing
- **Deterministic math:** anomalies, cash flow, and thresholds are computed in code, never by the LLM
- **Observability:** every run logs per-agent latency, tool calls, grounding scores, and token cost
- **Provider abstraction:** OpenAI, Anthropic, or a local deterministic provider, with keys kept server-side

`React` `TypeScript` `TanStack Start` `Tailwind` · [Live demo](https://fin-mind-weave.lovable.app)

### 📚 [AI Resource Library](https://github.com/Swetha-Pandala/ai-resource-library)
A curated, categorized catalog of the open-source AI repos I study and use: multi-agent systems, MCP and agent skills, LLM gateways, and automation tools. It has a JSON schema, validation workflows, and GitHub Actions that refresh repo metadata automatically.

## Tech I work with

| Area | Tools |
|---|---|
| **Agentic AI** | LangGraph, LangChain, Strands Agents, MCP, tool calling, agent memory, human-in-the-loop |
| **LLMs** | Amazon Bedrock (Claude, Llama), Azure OpenAI, OpenAI, Anthropic, Hugging Face Transformers |
| **Retrieval & evals** | pgvector, Pinecone, OpenSearch, Azure AI Search, embeddings, reranking, LangSmith |
| **ML** | PyTorch, TensorFlow, Scikit-learn, fine-tuning (GPT-2 on transaction data), spaCy |
| **Backend** | Python, FastAPI, AsyncIO, Pydantic, Celery, Java/Spring Boot, Kafka |
| **Frontend** | React, TypeScript, Tailwind CSS |
| **Data & cloud** | PostgreSQL, Redis, MongoDB, AWS, Azure, GCP, Docker, Kubernetes, GitHub Actions |

## What I'm exploring now

- Serving and evaluating **open-source LLMs** (Llama, Qwen, Mistral) with Ollama and vLLM
- **LoRA fine-tuning** small models for reliable tool calling
- Better **agent memory** and long-running agents with sandboxed tools
- Eval-driven development: making "is the agent better?" a number, not a feeling

## How I build

> Ground every answer. Measure before you ship. Keep the math in code. Treat user data as private by default.

## Let's connect

📫 **swethapandala799@gmail.com** · 📍 New York City area

I'm always happy to talk about agents, evals, and building AI products people actually use.
