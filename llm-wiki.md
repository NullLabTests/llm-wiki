# LLM Wiki

**A pattern for building personal knowledge bases using LLMs.**

This is an idea file — copy-paste it directly into your LLM agent (Claude, GPT, Grok, OpenAI Codex, etc.). The agent will collaborate with you to implement the full system.

## The core idea

Most people’s experience with LLMs and documents looks like RAG: you upload files, the model retrieves chunks at query time, and generates an answer.  
This works, but **the LLM rediscovers knowledge from scratch every single time**. Nothing accumulates. Ask a subtle question that requires synthesizing five documents and the model has to re-find and re-piece everything together. No persistent understanding is built.

**LLM Wiki flips this**: the LLM becomes a *knowledge engineer* that reads your raw documents once, actively compiles them into a clean, structured, interlinked Markdown knowledge base, and then *maintains* that base over time.

Raw documents stay immutable in `/raw/`.  
The synthesized, living wiki lives in `/wiki/`.  
Every new document or conversation updates the wiki with new syntheses, cross-links, and higher-level insights.

## How to use this file with your LLM

1. Create folders: `raw/` and `wiki/`
2. Drop your PDFs, notes, articles, etc. into `raw/`
3. Paste this entire file into your LLM and say:  
   > “You are now my LLM Wiki engineer. Build and maintain the wiki from the documents in raw/. Follow the pattern exactly.”

The agent will:
- Extract key concepts
- Synthesize summaries
- Create cross-links and backlinks
- Maintain a living table of contents
- Proactively suggest new connections

## Novel 2026 Extensions (fresh from arXiv)

Recent papers have supercharged this pattern with **persistent agentic memory**:

- **Knowledge Objects (KOs)** – Treat facts as atomic, first-class objects instead of fragile prompt text (arXiv:2603.17781, Mar 2026). Eliminates compaction loss and enables reliable multi-hop reasoning.
- **Graph-based RAG with memory replay** – AGRAG and ReMindRAG (2025–2026) add LLM-guided graph traversal and automatic consolidation.
- **Hierarchical persistent memory layers** – Systems like Memori and agentic memory hierarchies give the wiki true long-term accumulation without losing nuance.

You can instruct your LLM to incorporate these techniques when updating the wiki.

---

Start building your living knowledge base now.  
Just tell your LLM: “Initialize the LLM Wiki from the files in raw/ using the pattern above.”
