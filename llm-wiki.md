# LLM Wiki

Copy-paste this file into your LLM agent (Claude, GPT, Grok, etc.).

## Core Idea
Standard RAG has no accumulation — the model rebuilds understanding every time.  
**LLM Wiki** makes the LLM build and maintain a persistent Markdown knowledge base.

- Raw files → `raw/` (keep unchanged)
- Living wiki → `wiki/` (gets updated and refined)

## How to Use
1. Create `raw/` and `wiki/` folders
2. Put your notes/papers into `raw/`
3. Paste this file into your LLM and say:  
   "You are my LLM Wiki engineer. Build and maintain the wiki from raw/."

## 2026 Extensions
Use recent ideas like Knowledge Objects, graph memory replay, and agentic persistent memory for better long-term synthesis.

Start now: "Initialize the LLM Wiki using the pattern above."
