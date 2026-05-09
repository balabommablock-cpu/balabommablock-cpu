# rishabh balabomma

takes toys seriously. takes seriousness as a toy. shipping AI where hallucination is a regulatory violation — and a personal AI that actually remembers you.

solo. mumbai.

---

most AI demos break on edge cases. i build for domains where the edge case is the whole job — insurance pre-auth, financial compliance, regulatory interpretation. if it hallucinates, someone gets denied coverage or fails an audit.

i'm also building the personal AI i actually want — local-first, voice-native, with memory that survives more than a session. lives on whatsapp, on the web, on a phone in your pocket.

i also build tools that probably don't need to exist but are more fun because they do.

---

### what i'm building right now

**[hopefullyworks](https://hopefullyworks.vercel.app)** — a personal AI creature that runs on your machine, not someone's datacenter. ollama (llama3.2 + qwen2.5) + whisper.cpp + a custom memory engine. talks to you on whatsapp. wakes up at 3am to dream and consolidate memory (yes, an actual cron). voice loop in, voice loop out. mobile PWA on iOS and android via capacitor. the goal: an assistant where the model doesn't forget you between conversations and doesn't leak you to a vendor.

**[worn-memory](https://github.com/balabommablock-cpu/worn-memory)** — pluggable memory engine for AI agents. worn first-person doc + event-driven anticipation + sleep-time writer + hybrid retrieval. BYO database, LLM, embedder. the substrate behind hopefullyworks. open source.

**[ARIA Engine](https://github.com/balabommablock-cpu/aria-engine)** — fully autonomous content engine for X. claude opus writes, scores, schedules, publishes, and self-replies. 2,009 lines of python. 9 sqlite tables. zero manual intervention. the question isn't whether AI can write tweets. the question is whether it can develop taste.

**[PreAuth AI](https://github.com/balabommablock-cpu/preauth-ai)** — 5-node AI engine for hospital insurance pre-authorization. clinical parser, ICD-10 coding, completeness checker, approval scorer. parses Hindi-English mixed doctor's notes natively. days to minutes.

**[RegAI](https://github.com/balabommablock-cpu/regai)** — RAG pipeline for SEBI and RBI regulations. domain-specific chunking that preserves table context and amendment chains.

**[IndicFinEval-200](https://github.com/balabommablock-cpu/llm-eval-bfsi)** *(in progress, shipping june 2026)* — 200 hand-curated questions on indian financial regulation (SEBI, RBI, IRDAI), with golden answers and source citations. multi-model comparison across claude, gpt, gemini, sarvam. failure-mode taxonomy. the eval i wish existed before i started shipping claude in BFSI.

### research / writing

| paper | scope |
|---|---|
| **[The Delusional Manifesto](https://github.com/balabommablock-cpu/delusional-manifesto-wealthtech-india_)** | 22,000 words on AI-native personal finance in india. 10 chapters. 5 product specs. full system architecture. |

### proposed to anthropic (issues, not PRs yet)

- [anthropics/financial-services-plugins#15](https://github.com/anthropics/financial-services-plugins/issues/15) — indian BFSI plugin proposal. open.
- [anthropics/claude-cookbooks#407](https://github.com/anthropics/claude-cookbooks/issues/407) — domain-specific RAG cookbook. closed; team responded positively, awaiting implementation.

### day job

eight years of compounding into one narrow thing: how AI behaves inside regulated indian financial workflows.

- 2018 — strategy at redseer
- 2019 — growth at rapido
- 2020 — product at riskcovry (insurtech)
- 2022 → AVP product at motilal oswal (15,000-person listed firm; super app + pre-login)

---

[boredfolio.com](https://boredfolio.com) · [linkedin](https://www.linkedin.com/in/brishabhrao/) · [@BalabommaRao](https://x.com/BalabommaRao) · hello@boredfolio.com
