# LLM Wiki

**A pattern for building persistent personal knowledge bases with LLMs.**

Copy-paste this entire file into your LLM agent (Claude, GPT, Grok, etc.). The agent will become your dedicated **knowledge engineer**.

## The Core Idea
Standard RAG retrieves chunks and rebuilds understanding from scratch every time — there is **no accumulation**.  
**LLM Wiki** changes that forever: the LLM actively reads your raw documents and maintains a clean, structured, interlinked Markdown knowledge base that grows smarter with every update.

- Immutable source material lives in `/raw/`  
- Living, refined knowledge lives in `/wiki/` (constantly updated, linked, and synthesized)

Every new document or conversation triggers intelligent updates: new summaries, cross-references, higher-level insights, and refinements.

## How to Use
1. Create folders: `raw/` and `wiki/`  
2. Put your notes, papers, articles, PDFs, etc. into `raw/`  
3. Paste this file into your LLM and say exactly:  
   > "You are my LLM Wiki engineer. Build and maintain the wiki from the documents in raw/ using the pattern above."

The agent will extract concepts, synthesize, create backlinks, maintain a living table of contents, and suggest new connections.

## 2026 State-of-the-Art Extensions (fresh from arXiv)
Instruct your LLM to incorporate these recent breakthroughs when updating the wiki:

- **HiMem / H-MEM** — Hierarchical long-term memory architectures that organize knowledge by abstraction level for long-horizon reasoning (arXiv:2601.06377, 2507.22925)  
- **Agentic Memory (AgeMem)** — Unified framework that lets the agent itself manage long-term and short-term memory inside its policy (arXiv:2601.01885)  
- **Graph-based Agentic Memory** — Multi-graph hierarchies (insight/query/interaction graphs) with automatic tracing and consolidation (arXiv:2602.05665, G-Memory)  

These techniques eliminate compaction loss and enable true persistent synthesis.

Start building your living second brain now — just paste this file and give the initialization command above.
