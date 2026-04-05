# LLM Wiki

A pattern for building **persistent** personal knowledge bases using LLMs.

Copy-paste this file into your favorite LLM agent (Claude, GPT, Grok, etc.). The agent will act as your knowledge engineer.

## Core Idea

Standard RAG retrieves chunks and answers from scratch every time — no real accumulation happens.  
**LLM Wiki** changes that: the LLM reads your raw documents and actively builds a clean, interlinked Markdown knowledge base that improves over time.

- Raw documents stay in `/raw/` (immutable)
- Synthesized, living knowledge lives in `/wiki/`

Every new document or conversation triggers updates: new summaries, cross-links, higher-level insights, and refinements.

## How to Use

1. Create `raw/` and `wiki/` folders
2. Add your notes, papers, PDFs, etc. into `raw/`
3. Paste this whole file into your LLM and say:  
   > "You are my LLM Wiki engineer. Build and maintain the wiki from documents in raw/."

The LLM will extract concepts, synthesize, link, and keep the wiki organized.

## 2026 Novel Extensions

Recent arXiv papers add powerful techniques:
- **Knowledge Objects (KOs)** – atomic, persistent facts instead of fragile text
- Graph-based RAG with memory replay and hierarchical consolidation
- Agentic persistent memory systems that enable true long-term accumulation

Instruct your LLM to use these methods when updating the wiki.

Start now — tell your LLM: "Initialize the LLM Wiki using the pattern above."
