# LLM Wiki

**Persistent personal knowledge bases powered by LLMs.**

Traditional RAG forces the model to rediscover knowledge on every query.  
**This project implements Karpathy’s LLM Wiki pattern**: an LLM acts as a living knowledge engineer that ingests your raw documents and actively compiles, synthesizes, interlinks, and maintains a clean, evolving Markdown knowledge base.

**Goal**: Accumulate refined knowledge instead of rediscovering it. Your second brain that gets smarter over time.

### Quick Start
1. Drop source materials in `/raw/`
2. Paste `llm-wiki.md` into your favorite LLM agent (Claude, GPT, Grok, etc.)
3. Let the LLM build and update the `/wiki/` folder

### Novel 2026 Extensions (added from latest arXiv)
- **Knowledge Objects (KOs)** – facts as first-class, atomic, persistent objects (arXiv:2603.17781)  
- Graph-based memory replay & hierarchical consolidation (AGRAG, ReMindRAG, Memori)  
- Agentic persistent memory that avoids compaction loss and enables true synthesis

Star ⭐ if this helps you build your personal knowledge base!
