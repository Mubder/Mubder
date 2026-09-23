<div align="center">

# Mubder Alfaris

**Founder of [KazmaAI](https://kazma.ai) · I build self-hosted AI agents that ask before they act and tell the truth when they fail.**

Kuwait 🇰🇼 · [kazma.ai](https://kazma.ai) · [admin@kazma.ai](mailto:admin@kazma.ai) · [@b_alfaris](https://x.com/b_alfaris)

<a href="https://github.com/Mubder/kazma"><img src="https://img.shields.io/github/stars/Mubder/kazma?style=flat-square&label=kazma%20stars&color=6366F1&logo=github" alt="Kazma stars"></a>
<a href="https://github.com/Mubder/kazma/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/Mubder/kazma/ci.yml?branch=main&style=flat-square&label=kazma%20CI&logo=githubactions&logoColor=white" alt="Kazma CI"></a>
<a href="https://github.com/Mubder?tab=followers"><img src="https://img.shields.io/github/followers/Mubder?style=flat-square&color=10B981&logo=github" alt="Followers"></a>

</div>

---

## What I work on

I design and build autonomous AI agent systems, with a focus on the parts
that decide whether an agent can be trusted in daily use: human approval
before risky actions, long-term memory that can be inspected and corrected,
reliability under failure, and Arabic-native interaction.

I prefer measurement to claims. Kazma publishes its prompt-injection results
on a public benchmark — including the results that don't flatter it — and
keeps a dated list of its own known weaknesses.

## Featured

### [Kazma](https://github.com/Mubder/kazma) — self-hosted AI agent framework

One LangGraph supervisor reachable from Web, TUI, CLI, Telegram, Discord and
Slack.

- **Human-in-the-loop safety** — fail-closed approval on three independent
  paths, and a commitment layer that checks intent against memory before acting.
- **Cognitive memory** — bi-temporal beliefs, personalized-PageRank recall,
  hybrid lexical and vector search, encrypted and restorable backups.
- **Swarm orchestration** — six dispatch patterns, autoscaled workers and
  per-worker circuit breakers.
- **Document intelligence** — quarantined intake, sandboxed parsing and OCR,
  and correct Arabic and mixed-direction rendering.
- **Measured safety** — [prompt-injection results on AgentDojo](https://github.com/Mubder/kazma/blob/main/docs/INJECTION.md),
  a [threat model](https://github.com/Mubder/kazma/blob/main/docs/THREAT_MODEL.md)
  and [known gaps](https://github.com/Mubder/kazma/blob/main/docs/KNOWN_GAPS.md).

`Python` · `LangGraph` · `FastAPI` · `PostgreSQL` · `SQLite` · `Textual` · `Alpine.js` — MIT licensed.

### Also

| Project | What it is |
|---|---|
| [IndexArc](https://github.com/Mubder/IndexArc) | A portable personal vault for secrets, API keys and private knowledge, with local (Ollama) or cloud AI. TypeScript. |
| [LFGSuite](https://github.com/Mubder/LFGSuite) | An all-in-one group-finder and Mythic+ companion addon for World of Warcraft. Lua. |
| ShipX *(private)* | AI delivery platform that works over WhatsApp, with natural Khaleeji voice and text. |
| KCA *(private)* | Knowledge Capital Atlas — an engineering operating system for institutional knowledge and decisions. |

## Toolbox

| Area | Tools |
|---|---|
| Languages | Python · TypeScript · JavaScript · SQL · Lua · PowerShell · Bash |
| AI and agents | LangGraph · MCP · OpenAI · Anthropic · Gemini · DeepSeek · Ollama |
| Data and memory | PostgreSQL · SQLite (WAL, FTS5, sqlite-vec) · pgvector · Neo4j |
| Backend and ops | FastAPI · asyncio · Docker · restic · Cloudflare |
| Interfaces | Alpine.js · Textual · Telegram / Discord / Slack bots |

## Contact

Pilots, partnerships and collaboration: [admin@kazma.ai](mailto:admin@kazma.ai).
Security reports for Kazma: [private advisory](https://github.com/Mubder/kazma/security/advisories/new).
