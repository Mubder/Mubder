<div align="center">

# Mubder Alfaris

**Founder of [KazmaAI](https://kazma.ai) · I build self-hosted AI agents that ask before they act and tell the truth when they fail.**

Kuwait 🇰🇼

<a href="https://kazma.ai"><img src="https://img.shields.io/badge/Website-kazma.ai-06B6D4?style=flat-square" alt="Website: kazma.ai"></a>
<a href="https://x.com/KazmaAI"><img src="https://img.shields.io/badge/X-@KazmaAI-000000?style=flat-square&logo=x&logoColor=white" alt="@KazmaAI on X"></a>
<a href="https://x.com/b_alfaris"><img src="https://img.shields.io/badge/X-@b__alfaris%20(personal)-000000?style=flat-square&logo=x&logoColor=white" alt="@b_alfaris on X (personal)"></a>
<a href="mailto:admin@kazma.ai"><img src="https://img.shields.io/badge/Email-admin@kazma.ai-6366F1?style=flat-square" alt="Email: admin@kazma.ai"></a>

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

### [Kazma](https://github.com/Mubder/kazma) — the self-hosted AI agent that asks before it acts

One agent you reach from the browser, the terminal, Telegram, Discord or
Slack. It edits your repository, messages your team and runs your schedule,
pauses for your approval before anything risky, and says so when it fails
instead of inventing an answer.

<a href="https://github.com/Mubder/kazma"><img src="https://raw.githubusercontent.com/Mubder/kazma/main/docs/screenshots/chat-en.png" alt="Kazma's chat: an answer with the memory it used and the steps it took" width="100%"></a>

- **Human-in-the-loop safety** — approval before anything that writes, runs
  or sends, on every surface, and a commitment layer that checks intent
  against memory before acting.
- **Memory you can see and correct** — facts that keep when they were said
  and when they held, recall only above a measured threshold, and backups
  that are encrypted and restored in a daily drill.
- **Swarm orchestration** — six dispatch patterns, workers spawned on demand
  and the best model per task.
- **Document intelligence** — quarantined intake, sandboxed parsing and OCR,
  and correct Arabic and mixed-direction rendering.
- **Arabic-native** — a full right-to-left interface and documentation in
  English and Arabic.
- **Measured safety** — [prompt-injection results on AgentDojo](https://kazma.ai/docs/security/prompt-injection/),
  a [threat model](https://kazma.ai/docs/security/threat-model/)
  and [known gaps](https://kazma.ai/docs/security/known-gaps/).

**Get started:** [Install](https://github.com/Mubder/kazma#quick-start) ·
[Documentation](https://kazma.ai/docs/) · [Live demo](https://kazma-demo.fly.dev/)

`Python` · `LangGraph` · `FastAPI` · `PostgreSQL` · `SQLite` · `Textual` · `Alpine.js` — MIT licensed.

### Also

| Project | What it is |
|---|---|
| [IndexArc](https://github.com/Mubder/IndexArc) | A portable personal vault for secrets, API keys and private knowledge, with a local (Ollama) or cloud AI assistant. TypeScript. |
| [LFGSuite](https://github.com/Mubder/LFGSuite) | An all-in-one group-finder and Mythic+ companion addon for World of Warcraft. Lua. |
| [LFGAlert](https://github.com/Mubder/LFGAlert) | A World of Warcraft addon that alerts you when someone signs up for your group, and logs every applicant. Lua. |
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
On X: [@KazmaAI](https://x.com/KazmaAI) for Kazma, [@b_alfaris](https://x.com/b_alfaris) personally.
Security reports for Kazma: [private advisory](https://github.com/Mubder/kazma/security/advisories/new).
