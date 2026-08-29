## Nikunj Agrawal

**MS Computer Science, University of Pennsylvania.** I build AI systems, and the infrastructure that has to hold them up.

Hi, I'm Nikunj 👋

I build AI systems and the infrastructure required to keep them running. I've worked on Full-Stack development, agentic orchestration systems, Data systems and on what sits underneath all that: fault-tolerant storage, scaling retrieval across millions of documents, and making agentic workflows resilient.

🎓 Currently: Finishing my Master's in Computer Science at University of Pennsylvania.

💻 Building: AI Systems, MCP servers, and complex RAG pipelines.

🕰️ Previously: Spent 4 years in finance, strategy and SWE (CFA Level 1, product growth strategy, automating government technical workflows). I use that background to build AI tools that solve hard financial and operational problems and to use it grow and scale systems.

---

### Some of My Projects:

**[NCloud](https://github.com/nikunj474/ncloud)** : Fault-tolerant cloud platform (webmail, drive, chat) on a replicated, range-sharded key-value store written from scratch. ~16,000 lines of C++17 with no web framework, no ORM, and no database. Kill a storage node mid-upload and the cluster elects a new primary in about 1.5 seconds, the request completes, and the dead node resyncs when it returns.
*Team of 5. I owned the storage layer: the key-value server, replication wiring, multi-tablet sharding, and coordinator failover.*
`C++17` `replication` `leader election` `WAL + bloom filters` `SMTP` `Docker`

**[Financial MCP Server](https://github.com/nikunj474/financial-mcp-server)** : A Model Context Protocol server that gives any LLM live, tool-calling access to SEC EDGAR filings, 800k FRED economic series, and market fundamentals. Ask it to compare Apple's cash position against the Fed funds trend and it chains three tools to get there.
`Python` `MCP` `FastMCP` `agent tool design`

**[RAG Stock Retriever](https://github.com/nikunj474/RAG_Stock_predictor_model)** : Retrieval over ten years of S&P 500 news. DistilBERT embeddings generated on a local RTX 3090 with CUDA, stored in pgvector on AWS RDS, indexed with HNSW for sub-second similarity search across millions of headlines.
`DistilBERT` `pgvector` `HNSW` `CUDA` `AWS RDS`

**[Penn Planner](https://github.com/nikunj474/penn_planner)** : Wharton students track coursework in Canvas and recruiting in CareerPath, so nobody sees when four deadlines stack on one Tuesday. This pulls both into one ranked list and writes a daily Claude briefing.
`Next.js` `TypeScript` `Prisma` `Claude API`

**[FinPortco](https://github.com/nikunj474/finance-portco-app)** : Advisory CRM with JWT auth, per-advisor row ownership checks, SQLite FTS5 full-text search over client notes, and Claude-generated relationship summaries.
`React` `TypeScript` `Express` `SQLite FTS5` `Claude API`

---

### Tools I reach for

**Languages** Python, C++17, TypeScript, Java, SQL
**AI systems** MCP, LangChain, LangGraph, RAG, embeddings and vector search, evals, fine-tuning
**Backend** Node/Express, Next.js, FastAPI, Prisma, PostgreSQL, SQLite, Redis
**Infra** Docker, AWS (RDS, EC2, S3), GitHub Actions, Linux, CUDA

---

### Elsewhere

[nikunj-agrawal.com](https://nikunj-agrawal.com) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/nikunj3) &nbsp;·&nbsp; nikunjag24@gmail.com
