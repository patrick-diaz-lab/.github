# patrick-diaz-lab

A lab for exploratory work in **machine learning and AI** — agents, retrieval, evaluation, and the infrastructure around them.

Some projects run on self-hosted hardware, others use cloud models and services. The goal is to try ideas, measure what works, and keep what's worth keeping.

---

## 🧪 Projects

### Vision — `intelligence-center`
A personal "intelligence center": a central agent that knows its surrounding systems, files and notes, and can build and run its own tools.

- Custom **MCP servers** as the agent's interface to other systems
- Knowledge core backed by a synced Obsidian vault
- Planned: its own mailbox (reads and sends email) and rule-based model routing across providers

`Python` · `MCP` · `Agents` · `Proxmox` · `Tailscale` · `Obsidian`
**Status:** Phase 2 — MVP and knowledge core done, vault sync in progress

### Fedlex RAG
Retrieval-augmented question answering over **Swiss federal law (Fedlex)**, with answers anchored to cited articles to reduce hallucinations.

- Structure-aware chunking of legal texts (articles kept intact)
- Dense retrieval + cross-encoder re-ranking with a relevance floor
- Evaluated against a fixed question set
- Being rebuilt component by component using evaluation-driven development

`Python` · `BGE-M3` · `Qdrant` · `Docling` · `Ollama` · `RAG` · `Evaluation`
**Status:** Rebuild in progress

### homelab-media
Self-hosted media stack running separately from Vision.

- Usenet + *arr automation + Jellyfin, aiming for 4K / HDR playback
- Private access over Tailscale, requests via a Telegram bot

`Docker` · `Jellyfin` · `SABnzbd` · `*arr` · `Tailscale`
**Status:** Core stack built; paused on a Dolby Vision playback issue

---

## 🎯 Areas of interest

RAG · embeddings & re-ranking · LLM evaluation & observability · agents & MCP · self-hosted and cloud AI infrastructure

*More experiments to come.*
