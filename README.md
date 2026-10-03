<div align="center">

# Mubder Alfaris

**Founder of [KazmaAI](https://kazma.ai) · I build AI products that treat English and Arabic as equals, and agents that ask before they act.**

<a href="https://kazma.ai"><img src="https://img.shields.io/badge/Website-kazma.ai-06B6D4?style=flat-square" alt="Website: kazma.ai"></a>
<a href="https://x.com/KazmaAI"><img src="https://img.shields.io/badge/X-@KazmaAI-000000?style=flat-square&logo=x&logoColor=white" alt="@KazmaAI on X"></a>
<a href="https://x.com/b_alfaris"><img src="https://img.shields.io/badge/X-@b__alfaris%20(personal)-000000?style=flat-square&logo=x&logoColor=white" alt="@b_alfaris on X (personal)"></a>
<a href="mailto:admin@kazma.ai"><img src="https://img.shields.io/badge/Email-admin@kazma.ai-6366F1?style=flat-square" alt="Email: admin@kazma.ai"></a>

</div>

---

## What I work on

I build AI products for people and businesses in the Gulf and beyond,
bilingual by design: English and Arabic as equal first-class citizens, with
Gulf and Kuwaiti dialect handling, right-to-left interfaces, Arabic OCR and
Arabic voice. I care most about the parts that decide whether AI can be
trusted in daily use: approval before anything risky runs, memory you can
inspect and correct, and systems that verify outcomes instead of reporting
activity.

I prefer measurement to claims. Kazma publishes its prompt-injection results
on a public benchmark — including the results that don't flatter it — and
keeps a dated list of its own known weaknesses.

## Projects

### [Kazma](https://github.com/Mubder/kazma) — the flagship

*Open source (MIT) · v0.11 · Beta until 1.0*

A self-hosted AI agent platform, bilingual by design: English and Arabic as
equal first-class citizens, not Arabic as a nice-to-have. One agent serves you
across the web, the terminal, the CLI and your messaging apps (Telegram,
Discord, Slack), and around it sits a full workbench:

- **Web IDE** for working in your repositories;
- **X Studio** for composing, scheduling and managing X posts through the official API;
- **Knowledge Base** that grounds answers in your own documents and sources;
- **Deep Research**, a multi-source pipeline that produces full research papers, not quick search answers.

It is built for developers, operators and technical teams who want an agent
that actually works for them: long-term memory, human approval before
anything risky runs, and your own infrastructure. It is the most mature of my
projects, with more than 12,000 tests, a clean security audit, and a live
install I depend on every day. I keep the public release labelled Beta until
1.0, out of discipline more than doubt.

<a href="https://github.com/Mubder/kazma"><img src="https://raw.githubusercontent.com/Mubder/kazma/main/docs/screenshots/chat-en.png" alt="Kazma's chat: an answer with the memory it used and the steps it took" width="100%"></a>

**Get started:** [Install](https://github.com/Mubder/kazma#quick-start) ·
[Documentation](https://kazma.ai/docs/) · [Live demo](https://kazma-demo.fly.dev/) ·
[Security results](https://kazma.ai/docs/security/prompt-injection/)

`Python` · `LangGraph` · `FastAPI` · `PostgreSQL` · `SQLite` · `Textual` · `Alpine.js`

### ShipX — one AI layer for a merchant's whole business

*Private*

A one-place AI merchant platform, unified across channels: the merchant's
entire business runs through one AI layer over WhatsApp, Instagram and the
web (email included), with a single omnichannel inbox and one catalog synced
everywhere, not three disconnected apps. Catalog, orders, payments, returns
and customer conversations, in text or Arabic voice notes, all in one place.

- **Delivery that confirms itself.** It doesn't just dispatch: it confirms
  the courier accepted and picked up the order, and when a driver refuses or
  is busy it offers the run to the next available courier, with no one
  chasing drivers by hand.
- **Real-time fraud screening.** It watches order patterns (velocity spikes,
  unusual-hour bursts, abusive ordering) and sends high-risk orders to a human
  instead of dispatching them.

Starting in Kuwait, then the GCC and the wider Middle East, on an
architecture kept deliberately global-ready.

### HypertFit — an all-in-one AI fitness platform

*Private*

"All-in-one" is the whole point. It serves trainees, and coaches run their
rosters on it; supplement stores and diet restaurants sell into its
marketplace, and gyms get their own tenancy. One ecosystem built around the
training plan.

### KCA — Knowledge Capital Atlas

*Private · before Beta*

The biggest and most ambitious of my projects: an AI operating system for
companies. It doesn't just hold tasks — it follows them. Every employee gets
a workspace and a sub-agent that turns conversations into tasks, tracks
progress and nudges with reminders. The system watches for stalled work,
bottlenecks and overdue items, guides people through how to accomplish what
is assigned, and verifies "done" by evidence: activity is not achievement.
Admins get their own management layer and roles, and the founders see
verified completions and escalated exceptions instead of noise. Around that
core: multi-agent feasibility analysis for new ventures, continuous risk
monitoring with bilingual alerts, and company knowledge graphs. It needs the
most time before Beta, and I'd rather give it that time than rush it.

### [IndexArc](https://github.com/Mubder/IndexArc)

*Open source*

A portable, ultra-secure personal vault for secrets, API keys and private
knowledge, with a local (Ollama) or cloud AI assistant. TypeScript.

## Toolbox

| Area | Tools |
|---|---|
| Languages | Python · TypeScript · JavaScript · SQL · PowerShell · Bash |
| AI and agents | LangGraph · MCP · OpenAI · Anthropic · Gemini · DeepSeek · Ollama |
| Data and memory | PostgreSQL · SQLite (WAL, FTS5, sqlite-vec) · pgvector · Neo4j |
| Backend and ops | FastAPI · asyncio · Docker · restic · Cloudflare |
| Interfaces | Alpine.js · Textual · Telegram / Discord / Slack · WhatsApp · Instagram |

## Contact

Pilots, partnerships and collaboration: [admin@kazma.ai](mailto:admin@kazma.ai).
On X: [@KazmaAI](https://x.com/KazmaAI) for Kazma, [@b_alfaris](https://x.com/b_alfaris) personally.
Security reports for Kazma: [private advisory](https://github.com/Mubder/kazma/security/advisories/new).
