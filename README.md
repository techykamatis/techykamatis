# Vhen Joseph Fernandez

**AI & software engineering leader — 14+ years shipping production systems.**
Currently AI Product Engineer Lead at YTL AI Labs, integrating an in-house LLM
(ILMU) into consumer-facing products running on AWS EKS.

Most of my code lives in **private enterprise repositories**, so this profile is
intentionally sparse. For full experience, projects, and references:

- 💼 LinkedIn: https://linkedin.com/in/vhenjoseph
- ✉️ vhenjoseph@gmail.com
- 📍 Kuala Lumpur, Malaysia

### What I do
- **Backend & API architecture** for fast-moving teams
- **AI-native engineering** — LLM integration, RAG, agentic systems, prompt engineering (not "just call an LLM")
- **Production reliability** — Kubernetes on AWS EKS, CI/CD, observability, testing critical flows
- **Hands-on technical leadership** — mentoring engineers, reviewing junior & AI-generated code, defining engineering SOPs that scale teams

### Stack
**Recent:** LLM integration · RAG · agentic systems · Kubernetes · AWS (EKS / EC2 / S3 / IAM) · Docker · CI/CD · testing
**Earlier:** PHP · Laravel · React · MySQL · J2EE · C# / CUDA

### Selected project — Candice, a Family AI System (2026)

An always-on, local-first AI butler I built for my family. It lives in iMessage,
keeps a separate long-term memory and persona per person, and reaches out
proactively (morning briefs, weekly digests, anomaly nudges) rather than waiting
to be asked.

**Architecture & write-up →** https://evcandice.github.io/candice/ · **Case study →** https://github.com/techykamatis/candice

- **Local-first** — models, memory, and media processing run on a home Mac; only
  message text touches an external LLM API
- **Memory** — per-person vector namespaces (mem0 + Chroma) with local embeddings
  and fact extraction via Ollama (nomic-embed-text, qwen3:4b)
- **Proactive engine** — asyncio trigger loop with cooldowns, muting, anti-spam
- **Agentic & self-maintaining** — sandboxed task runner; nightly test-gated
  self-update with automatic rollback
- **Stack** — Python · FastAPI · asyncio · mem0 · Chroma · Ollama · Next.js · SQLite (WAL) · launchd
