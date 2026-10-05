### Hi, I'm Thong 👋

**Fullstack / AI Engineer** in Ho Chi Minh City. I've been building for the web since 2018 — React and TypeScript on large-scale products at **Naver Vietnam (Weverse)**, CJ OliveNetwork and Brickmate — and now I take products end to end: database schema, API, AI agent, web client, CI/CD and the server they run on.

- 🏢 Frontend Developer at Naver Vietnam, on the Weverse platform: Webpack Module Federation micro-frontends and multi-app monorepos
- 🤖 Focused on applied AI: LangGraph multi-agent systems, human-in-the-loop, RAG, natural-language-to-SQL, eval harnesses
- 🛠️ I build, deploy and run my own products on a VPS I operate myself
- ✍️ I write about what I build at [blog.hanu-nus.com](https://blog.hanu-nus.com)

---

### 🚀 Live products

| | Product | What it does | Stack |
|---|---|---|---|
| 💰 | **[Family Finance](https://finance.hanu-nus.com)** | Household finance app built around an AI agent, used daily by real households. A LangGraph pipeline turns a bank PDF or phone photo into ledger rows for human review — **precision 1.00, recall 0.996, zero hallucinated lines** on real multi-bank statements. A multi-flow chat agent answers questions over the family's own data, with guarded NL-to-SQL and hybrid RAG. Built solo, ~115K LOC. | Next.js 16 · NestJS 11 · MySQL · Drizzle · LangGraph.js · Weaviate · LangSmith |
| 📄 | **[Resume Builder](https://resume.hanu-nus.com)** | Free resume builder: 40 templates with live PDF preview, AI import of an existing CV, tailoring to a job description, ATS check, cover letters and job matching — in English, Vietnamese and Korean. The AI only suggests; the user applies, with undo. | TanStack Start · Effect · PostgreSQL · LangGraph.js · BullMQ · Redis |
| ✍️ | **[Tech Blog](https://blog.hanu-nus.com)** | Blog platform with its own CMS: Markdown/rich-text editor, server-rendered code and Mermaid diagrams, scheduled publishing, accent-insensitive search, moderated comments. | Next.js · NestJS · MongoDB · Prisma |

All three ship on every push: GitHub Actions → Docker images on GHCR → self-hosted runner on my VPS, behind nginx — gated by tests, typecheck and lint.

---

### 🧪 Open-source AI work

- **[land-law-chatbot](https://github.com/thongvmdev/land-law-chatbot)** — Agentic RAG chatbot for Vietnam Land Law 2024: a 9-node LangGraph workflow (query decomposition, parallel retrieval, document grading, iterative refinement), hybrid Weaviate + BM25 retrieval over a hierarchical legal corpus.
- **[chat-langchain-practice](https://github.com/thongvmdev/chat-langchain-practice)** — Migration of a production chatbot backend from Python to TypeScript: agentic RAG StateGraph with a researcher subgraph, evaluated with Vitest + LangSmith (retrieval recall > 0.9, answer correctness > 0.9).

---

### 🧰 Tech stack

- **Frontend** — TypeScript · React · Next.js · TanStack (Start, Query) · Zustand · MUI · Ant Design · Tailwind · Webpack Module Federation
- **Backend** — Node.js · NestJS · Effect · MySQL · PostgreSQL · MongoDB · Drizzle · Prisma · Redis · BullMQ
- **AI** — LangGraph.js · LangChain · RAG · Weaviate · VLM document pipelines · LangSmith evals
- **Delivery** — Turborepo · Docker · GitHub Actions · nginx · Vitest · Playwright
- **Daily tools** — Claude Code · Cursor

---

### 📫 Contact

[![Email](https://img.shields.io/badge/Email-thongvmdev%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:thongvmdev@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vo%20Minh%20Thong-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/v%C3%B5-minh-th%C3%B4ng-6a9843114/)
[![Blog](https://img.shields.io/badge/Blog-blog.hanu--nus.com-111111?logo=readdotcv&logoColor=white)](https://blog.hanu-nus.com)
