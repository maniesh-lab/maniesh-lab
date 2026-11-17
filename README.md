# Hi, I'm Manish

Self-taught Python developer building **AI agents, RAG systems and automation backends**.
I ship things I can explain end to end, with tests, evals and docs. No black boxes, mine included.

---

## Featured: [lookup-agent](https://github.com/maniesh-lab/lookup-agent)

<a href="https://github.com/maniesh-lab/lookup-agent"><img src="https://raw.githubusercontent.com/maniesh-lab/lookup-agent/main/docs/images/demo.gif" alt="lookup-agent answering questions with its sources" width="420" align="right"></a>

A chatbot agent that **looks things up before it answers**. It searches policy documents, queries a Postgres database safely, and calls a live exchange-rate API, then shows exactly where each fact came from.

- **LangGraph** agent with tool calling, memory and a step cap
- **Hybrid search** (pgvector + keyword + reranker) and a read-only, locked-down SQL tool
- **Evals with real numbers**: 40/41 on the main set, 15/15 on a set of trap and reasoning questions
- **Production basics**: FastAPI, Docker Compose, CI with coverage on Codecov, Langfuse tracing
- A chat page with sources, light and dark mode, and a stop button

<br clear="right">

---

## Projects

| Project | What it does | Built with |
|---|---|---|
| [lookup-agent](https://github.com/maniesh-lab/lookup-agent) | AI agent over documents, a database and a live API, with sources and evals | LangGraph, FastAPI, Postgres + pgvector, Docker |
| [leadgate](https://github.com/maniesh-lab/leadgate) | Lead generation with a human in charge: agents find local businesses, read their sites, clean, dedupe and score each lead, and nothing reaches the CRM until a person approves it. [Live demo](https://leadgate-ocu8.onrender.com) | LangGraph, FastAPI, Postgres, React, n8n |
| [askfirst](https://github.com/maniesh-lab/askfirst) | AI agents that ask before they act: a browser agent that fills web forms and stops for your approval before it submits, plus a scheduled GitHub issue-triage bot that posts a Discord digest and only proposes anything public. 282 tests, 93% coverage. [Live practice site](https://askfirst-practice.onrender.com) | LangGraph, Playwright, GitHub Actions, Docker |
| [Steadfast](https://github.com/maniesh-lab/steadfast) | Reliability layer for LLM APIs: retries, rate limits, provider fallback, tool calling, validate-and-retry. On PyPI as `steadfast-llm` | Python, Pydantic, httpx |
| [ragdocs](https://github.com/maniesh-lab/ragdocs) | RAG chatbot for your documents, with an eval layer | FastAPI, Chroma, Streamlit |
| [Hearth](https://github.com/maniesh-lab/Hearth) | Discord bot that runs a community server: onboarding, self-serve roles, moderation with a mod log, a deadline board and respect points, plus an AI FAQ that answers from the server's own docs instead of matching keywords | discord.py, Gemini embeddings, Groq, SQLite |

---

## Currently

Building a freelance track record on Upwork: AI agents and RAG, FastAPI backends, scraping (Scrapy, Playwright) and automation (n8n, Docker).

## Tech stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/langgraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Langfuse](https://img.shields.io/badge/langfuse-0A0A0A?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Airtable](https://img.shields.io/badge/airtable-18BFFF?style=for-the-badge&logo=airtable&logoColor=white)
![Discord](https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scrapy](https://img.shields.io/badge/scrapy-%2360A839.svg?style=for-the-badge&logo=scrapy&logoColor=white)
![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Tailwind CSS](https://img.shields.io/badge/tailwind%20css-%2338B2AC.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
