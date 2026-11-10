# Hi, I'm Rodrigo 👋

### AI Engineer · MSc in Informatics & Computing Engineering (FEUP)

I build LLM-powered applications, with a focus on **Retrieval-Augmented Generation (RAG)** and **LLM agents**.

For my master's thesis I designed and built a **RAG-based generative question-answering system**. I implemented the full retrieval-and-generation pipeline from scratch in Python (no orchestration frameworks), calling LLM APIs for the generation step. A full paper on this work has been submitted to ECIR, and a resource paper is in progress.

I extended that system into a **multi-turn conversational search engine** built with LangGraph.

- 🔭 **Currently:** building LLM agents that are safe to run on real systems (latest: [Legacy Password Rotation Agent](https://github.com/RodrigoCamposRodrigues/legacy-password-rotation-agent))
- 🌱 **Exploring:** agent reliability and evaluation, and taking LLM systems to production (CI, containers, monitoring)
- 🎯 **Open to:** Junior AI Engineer roles
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/rcr21/) · [rodrigues.rodrigo2003@gmail.com](mailto:rodrigues.rodrigo2003@gmail.com)

## 🛠️ Tech stack

**AI / ML:** Python · LangGraph · LangChain · LLM APIs · Retrieval-Augmented Generation (RAG) · Embeddings & semantic search · Information retrieval (Apache Solr) · Browser agents (Playwright) · LLM evals & tracing (LangSmith)

**Engineering:** FastAPI · Docker · PostgreSQL · SQLite · Git

## 📌 Featured projects

| Project | What it is |
|---------|------------|
| [Legacy Password Rotation Agent](https://github.com/RodrigoCamposRodrigues/legacy-password-rotation-agent) | An LLM browser agent that rotates device passwords through a legacy web dashboard with no API, and never loses one, even if it crashes mid-change. A LangGraph write-ahead protocol owns the safety steps, gated Playwright tools keep every password away from the model, and crash-injection tests and LangSmith evals back it up. |
| [Agent Security Harness](https://github.com/RodrigoCamposRodrigues/agent-security-harness) | A harness that attacks two LLM agents with prompt injection (my password rotation agent and a shared-inbox email assistant) and measures how often each attack works, with every defence on, off and one at a time. Plain-code checks on what the agent actually did, no LLM judge: 4,243 runs with 95% confidence intervals, mapped to the OWASP Top 10 for LLMs and agents. |
| [World Cup Conversational Search](https://github.com/RodrigoCamposRodrigues/world-cup-conversational-search) | A conversational search assistant over a fictional World Cup dataset: a LangGraph workflow resolves follow-ups and asks clarifying questions, and a validated query planner retrieves evidence from Solr for source-cited answers. |
| [Automotive Review Search Engine](https://github.com/RodrigoCamposRodrigues/FEUP-PRI) | A search engine over automotive reviews using information-retrieval techniques (indexing, ranking, relevance evaluation) — the retrieval foundations behind RAG. |
| [AI4SD: AI for Software Development](https://github.com/RodrigoCamposRodrigues/FEUP-DS) | A 150+ student project building AI assistants for the software development lifecycle. In the Verification & Validation area, my team built req2test, which turns requirements into Gherkin acceptance tests with Gemini. |
| [Feupbook](https://github.com/RodrigoCamposRodrigues/feupbook) | A full-stack social network for FEUP students, built end-to-end with Laravel and Bootstrap. |
| [Local-First Shopping List](https://github.com/RodrigoCamposRodrigues/FEUP-SDLE) | A local-first, distributed shopping-list application from a large-scale distributed systems course. |

## Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rcr21/)
[![Email](https://img.shields.io/badge/rodrigues.rodrigo2003%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rodrigues.rodrigo2003@gmail.com)
