# rishabh balabomma

takes toys seriously. takes seriousness as a toy. shipping AI where hallucination is a regulatory violation — and a personal AI that actually remembers you.

26 repos. solo. mumbai. contributing to [@anthropics](https://github.com/anthropics).

---

most AI demos break on edge cases. i build for domains where the edge case is the whole job — insurance pre-auth, financial compliance, regulatory interpretation. if it hallucinates, someone gets denied coverage or fails an audit.

i'm also building the personal AI i actually want — local-first, voice-native, with memory that survives more than a session. lives on whatsapp, on the web, on a phone in your pocket.

i also build tools that probably don't need to exist but are more fun because they do.

---

### what i'm building right now

**[hopefullyworks](https://hopefullyworks.vercel.app)** — a personal AI creature that runs on your machine, not someone's datacenter. ollama (llama3.2 + qwen2.5) + whisper.cpp + a custom memory engine. talks to you on whatsapp. wakes up at 3am to dream and consolidate memory (yes, an actual cron). voice loop in, voice loop out. mobile PWA on iOS and android via capacitor. the goal: an assistant where the model doesn't forget you between conversations and doesn't leak you to a vendor.

**[worn-memory](https://github.com/balabommablock-cpu/worn-memory)** — pluggable memory engine for AI agents. worn first-person doc + event-driven anticipation + sleep-time writer + hybrid retrieval. BYO database, LLM, embedder. the substrate behind hopefullyworks. open source.

**[ARIA Engine](https://github.com/balabommablock-cpu/aria-engine)** — fully autonomous content engine for X. claude opus writes, scores, schedules, publishes, and self-replies. 2,009 lines of python. 9 sqlite tables. zero manual intervention. the question isn't whether AI can write tweets. the question is whether it can develop taste.

**[Claude Web Studio](https://github.com/balabommablock-cpu/claude-web-studio)** — 28 specialist agents. drop a CLAUDE.md into any project and get accessibility, security, SEO, and legal compliance enforced automatically while you build. the orchestrator is prohibited from writing code or making decisions. it can only route. this solves the #1 problem with multi-agent systems.

**[PreAuth AI](https://github.com/balabommablock-cpu/preauth-ai)** — 5-node AI engine for hospital insurance pre-authorization. clinical parser, ICD-10 coding, completeness checker, approval scorer. parses Hindi-English mixed doctor's notes natively. days to minutes.

**[unga-bunga](https://github.com/balabommablock-cpu/unga-bunga)** — your CLAUDE.md is a gym membership you forgot to cancel. except it charges you every message. this audits your setup, compresses the bloat, and saves up to 72% of your Claude Code token spend.

### also shipped

| project | what it does |
|---|---|
| **[Boredfolio / Jugalbandi](https://github.com/balabommablock-cpu/boredfolio)** | india's most transparent mutual fund platform + dual-interface wealth management system. next.js 15 monorepo. |
| **[Open Mithiya](https://github.com/balabommablock-cpu/openmithiya)** | benchmark-optimized agentic coding CLI. forked from codex, closing 9 gaps vs claude code. rust. |
| **[Claude Mobile Studio](https://github.com/balabommablock-cpu/claude-mobile-studio)** | 26 specialist agents for mobile dev. HIG/Material compliance, App Store readiness, ASO — enforced automatically. |
| **[claude-on-a-budget](https://github.com/balabommablock-cpu/claude-on-a-budget)** | token compression for Claude Code. honest about caching. AST-level compression. behavioral regression testing. |
| **[RegAI](https://github.com/balabommablock-cpu/regai)** | RAG pipeline for SEBI and RBI regulations. domain-specific chunking that preserves table context and amendment chains. |
| **[Job Autopilot v3](https://github.com/balabommablock-cpu/job-autopilot-v3)** | 7-stage AI outreach pipeline. scrape, guardrails, score, compose, resume gen, send, monitor. 2,500+ lines of python. |
| **[Resume Scorer](https://github.com/balabommablock-cpu/resume-scorer)** | 6-dimension AI resume scoring. semantic skill matching, bias detection, explainable reasoning. |

### research

| paper | scope |
|---|---|
| **[The Delusional Manifesto](https://github.com/balabommablock-cpu/delusional-manifesto-wealthtech-india_)** | 22,000 words on AI-native personal finance in india. 10 chapters. 5 product specs. full system architecture. |
| **[Agentic WealthOps](https://github.com/balabommablock-cpu/agentic-wealthops)** | 52 use cases for AI agents in indian broking, MF distribution, and insurance. |
| **[Claude for Indian BFSI](https://github.com/balabommablock-cpu/claude-for-indian-bfsi)** | claude go-to-market playbook for indian banking. RBI compliance mapping, production prompt templates. |

### contributing to anthropic

- [anthropics/financial-services-plugins#15](https://github.com/anthropics/financial-services-plugins/pull/15) — indian BFSI plugin
- [anthropics/claude-cookbooks#407](https://github.com/anthropics/claude-cookbooks/pull/407) — domain-specific RAG cookbook

[boredfolio.com](https://boredfolio.com) · [linkedin](https://www.linkedin.com/in/rishabh-balabomma/) · [@BalabommaRao](https://x.com/BalabommaRao)
