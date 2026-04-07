# LLM Wiki

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/NullLabTests/llm-wiki/blob/main/LICENSE)

**Persistent personal knowledge bases powered by LLMs — beyond RAG.**

Traditional retrieval-augmented generation (RAG) forces models to rediscover knowledge on every query.  
**LLM Wiki** transforms the LLM into a dedicated knowledge engineer that builds and maintains a clean, interlinked, evolving Markdown second brain from raw documents.

**Goal**: Accumulate refined, hierarchical knowledge over time instead of starting from scratch on each interaction.

### Quick Start (30 seconds)
1. Drop your documents, notes, or PDFs into the `raw/` folder  
2. Copy the content of `llm-wiki.md`  
3. Paste into any frontier LLM (Grok, Claude, GPT, etc.) and prompt:  
   > "You are my LLM Wiki knowledge engineer. Build and maintain the wiki from the documents in raw/."

### 2026 Research Foundations
This implementation is directly grounded in the latest arXiv literature on AGI-adjacent memory systems:
- **HiMem: Hierarchical Long-Term Memory for LLM Long-Horizon Agents** (Zhang et al., arXiv:2601.06377, 2026)  
- **H-MEM: Hierarchical Memory for High-Efficiency Long-Term Reasoning in LLM Agents** (Sun et al., arXiv:2507.22925, 2025)  
- **A-MEM: Agentic Memory for LLM Agents** (Xu et al., arXiv:2502.12110, 2025)  
- **G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems** (Zhang et al., arXiv:2506.07398, 2025)  
- ARC Prize 2025 Technical Report (Chollet et al., arXiv:2601.10904) and related AGI abstraction surveys

### Star ⭐ if you are building real persistent intelligence.
Inspired by @karpathy’s original LLM Wiki concept.  
[Follow on X](https://x.com/TheGoldenAnvil) | [Open an issue](https://github.com/NullLabTests/llm-wiki/issues)

Contributing: Add real documents to `raw/`, run the prompt, and open a PR with improvements to the `wiki/` folder.
