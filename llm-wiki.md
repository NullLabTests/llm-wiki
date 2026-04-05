# LLM Wiki

Copy-paste this entire file into your LLM agent.

## Core Idea
Standard RAG has no real accumulation. The model rebuilds understanding from chunks every time.  
**LLM Wiki** makes the LLM act as a knowledge engineer: it reads raw documents and maintains a structured, interlinked Markdown wiki that improves over time.

- Raw files stay in `/raw/` (immutable)
- Living knowledge lives in `/wiki/`

## How to Use
1. Create `raw/` and `wiki/` folders
2. Put your materials in `raw/`
3. Paste this file into your LLM and say:  
   "You are my LLM Wiki engineer. Build and maintain the wiki from the documents in raw/."

## 2026 Novel Extensions
Incorporate recent ideas such as **Knowledge Objects**, graph-based memory replay, and agentic persistent memory for better synthesis and long-term retention.

Start building: "Initialize the LLM Wiki using the pattern above."
