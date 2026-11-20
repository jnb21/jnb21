Salut / Hi, I'm Jordan 👋
Backend & AI Developer. I build APIs and AI-powered apps in Python and Java, with a focus on getting the hard parts right: data that stays consistent, permissions enforced in code, and AI features with real guardrails.
🎓 Computer Science @ Concordia University (expected 2028) 💼 Open to backend and AI developer roles, and summer 2027 internships · Montréal · Bilingual EN/FR 🌐 Portfolio · LinkedIn
🚀 Featured Projects
Job Application Tracker + "Ask" AI agent · Live A full-stack app for tracking job applications. Paste a job link and Claude extracts the key requirements. The built-in agent answers questions over your saved postings using RAG in English and French (pgvector + multilingual embeddings). Guardrails: every search is scoped to the user, daily question and token limits (HTTP 429), cost logged per question, and the agent goes through the API with the user's token instead of touching the database. Tested with pytest against real Postgres in GitHub Actions CI. Python FastAPI PostgreSQL pgvector React Claude Docker AWS
Double-Entry Ledger API A ledger where the database enforces the rules: debits must equal credits (deferred trigger at COMMIT), history is append-only, and mistakes are fixed with reversal entries. Accounts are locked in id order to prevent deadlocks, and idempotency keys make sure a retried request never posts twice. Testcontainers tests fire 50 concurrent withdrawals and check that exactly the right number succeed. Java 21 Spring Boot PostgreSQL Flyway JUnit 5 Testcontainers
Budget App Budgets, transactions and a dashboard, with Postgres Row-Level Security so the database itself hides other users' rows. Includes rate limiting, "download my data" and "delete my account." Infrastructure defined as code with AWS CloudFormation. Python FastAPI PostgreSQL React Docker AWS CloudFormation
RAG System Retrieval-augmented generation built step by step: ingest, retrieve, augment, generate. Before using a real embedding model, I wrote a toy embedder by hand to understand what the model actually does. Answers cite their sources. Python ChromaDB sentence-transformers LangChain Claude Streamlit
🧰 Stack
Languages: Python · Java · SQL · JavaScript · C++
Backend: FastAPI · Spring Boot · PostgreSQL · MySQL · Alembic · Flyway
Frontend: React · Vite · HTML/CSS · Streamlit
AI: Claude API · tool use · AI agents · RAG · pgvector · ChromaDB · embeddings
Cloud & Tools: AWS · Docker · GitHub Actions · Git
Testing: pytest · JUnit 5 · Testcontainers
⚡ About me
I like understanding why systems work, not just making them work. I'm especially interested in fintech and in systems where correctness matters.
💡 Always happy to talk about backend design, AI agents, or anything you're building.

