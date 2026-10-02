# Hi, I'm Vinayak (Shubb)

Final-year Computer Science student at PES University, Bengaluru. I build backend systems in Python and FastAPI, with a focus on correctness, testing, and LLM-powered features.

## What I've built

- **[Automated Financial Data Analysis System](https://github.com/VinayakShubb/Automated-Financial-Data-Analysis-System)**: fraud investigation platform for bank statements. Deterministic 25-detector fraud engine, NetworkX money-flow graphs, and a RAG chatbot over case data. Validated on 162 real bank statements (200,000+ transactions) from CID investigators. Runner-up at CIDECODE Hackathon 2026 (top 2 of 42 finalist teams, 500+ applicants).
- **[sluiceee](https://github.com/VinayakShubb/sluiceee)**: async rate-limiting library for FastAPI/Starlette. Four algorithms behind one interface, in-memory and Redis backends (each Redis decision is one atomic Lua script). A test fires 500 concurrent requests and checks that exactly the configured limit gets through. About 96% coverage, CI across Python 3.9 to 3.13, mypy --strict.
- **[ASCEND](https://github.com/VinayakShubb/ASCEND)**: AI habit tracker. The FastAPI backend validates the JWT on every route and is the only service that talks to the LLM. React + TypeScript frontend, Supabase Postgres, 93-test pytest suite.

## Stack

**Backend:** Python, FastAPI, asyncio, REST APIs, PostgreSQL, SQLite

**Testing and CI:** pytest, pytest-cov, mypy, GitHub Actions

**AI:** LLMs, prompt engineering, RAG with ChromaDB

## Contact

vinayakshub6@gmail.com · [LinkedIn](https://linkedin.com/in/vinayak-g-k)
