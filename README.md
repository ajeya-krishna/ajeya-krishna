## Ajeya Krishna

**AI Engineer. I build production GenAI systems: real-time voice agents, agentic automations, RAG, and the evals and tracing that keep them reliable.**

AI Engineer at **BukuWarung** (Jakarta) · previously ML Engineer II at **SaaS Labs** (Bangalore) · IIT (BHU) Varanasi

4+ years shipping AI to production, with **$3M+ in direct revenue** from the systems I built.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ajeya%20Krishna-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajeya-krishna12/)
[![Email](https://img.shields.io/badge/Email-ajjukrish2000%40gmail.com-555?style=flat-square&logo=gmail&logoColor=white)](mailto:ajjukrish2000@gmail.com)

---

### Open-source contributions

**Contributor to PipesHub and Pipecat**, with merged fixes for streaming, citation accuracy and dependency compatibility.

**4 merged PRs · 10 open PRs** · October 28, 2026

#### Merged fixes

| Project | Problem fixed | PR |
|---|---|---|
| **PipesHub** | Valid streaming events were silently dropped. Fixed SSE field parsing, unnamed events and state reset between frames. | [#4750 — Merged](https://github.com/pipeshub-ai/pipeshub-ai/pull/4750) |
| **PipesHub** | Citation links could split contractions in mixed CJK/Latin text. Preserved word boundaries when generating text fragments. | [#4749 — Merged](https://github.com/pipeshub-ai/pipeshub-ai/pull/4749) |
| **PipesHub** | CSS custom properties and quoted strings could hide visible text from citations. Replaced raw substring matching with CSS parsing. | [#4751 — Merged](https://github.com/pipeshub-ai/pipeshub-ai/pull/4751) |
| **Pipecat** | The dependency constraint blocked installation alongside Pillow 13. Updated the constraint and lockfile to support it. | [#6286 — Merged](https://github.com/pipecat-ai/pipecat/pull/6286) |

Each fix includes regression tests. The streaming update passed **3,833 frontend tests** and TypeScript checks locally; the Pillow update passed 153 focused tests on both versions and upstream CI.

<details>
<summary><strong>10 open PRs across Langfuse, LiveKit, Pipecat, LlamaIndex, aiocache and Ollama</strong></summary>

- **Langfuse:** [release detection when CI variables are empty](https://github.com/langfuse/langfuse-python/pull/2042). Updated branch passes **978 unit tests** locally; awaiting upstream checks and merge.
- **LiveKit Agents:** [keep image-fit dimensions positive](https://github.com/livekit/agents/pull/8058) and [make instruction hashes consistent with string equality](https://github.com/livekit/agents/pull/8066).
- **Pipecat:** [close OpenAI-compatible clients during cleanup](https://github.com/pipecat-ai/pipecat/pull/6284).
- **LlamaIndex:** [parse extended HWP record lengths](https://github.com/run-llama/llama_index/pull/23650) and [normalize Obsidian vault paths for metadata](https://github.com/run-llama/llama_index/pull/23654).
- **aiocache:** [safe Valkey cache representation before connecting](https://github.com/aio-libs/aiocache/pull/1089), [cancel stale TTL timers on clear](https://github.com/aio-libs/aiocache/pull/1090), and [handle empty batch reads in cache metrics](https://github.com/aio-libs/aiocache/pull/1091).
- **Ollama:** [preserve model temperature defaults in the completions API](https://github.com/ollama/ollama/pull/19237).

</details>

### What I've shipped

- **Voice AI agent (SaaS Labs):** real-time calling agent (STT → LLM → TTS) that lifted revenue 30% and has generated **$1.5M+** since launch. Runs on GCP with Kubernetes at **P99 < 1 s**.
- **Voice platform (BukuWarung):** LiveKit + Twilio agents for customer support, lending reminders and telesales. Cut support escalations by **~70%**.
- **Voice navigation for merchants:** bilingual (Indonesian/English) voice control for transfers, payments and app actions. **~40%** adoption uplift with a **< 1%** misinterpretation rate.
- **Agentic automation:** 20+ automations across People, Finance, Marketing and Ops, saving **~1,500 hrs/month**. Includes AI agents for crisis escalation, invoice processing (OCR + LLM) and travel-policy approvals.
- **Conversational intelligence (JustCall IQ):** led call summaries, AI call scoring, and AI tags and priority, used by 30+ businesses.
- **LLMOps:** Langfuse tracing across every production agent, plus an LLM evaluation and prompt-engineering pipeline on AWS and GCP.

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**ControlTower**](https://github.com/ajeya-krishna/ControlTower) | One chat interface for insurance ops. An LLM planner and a rule-based supervisor coordinate three workflows, and every step is checkpointed to Postgres, so a session survives a backend crash. Deployed on AWS, with a write-up of 5 faults that only live traffic exposed. | LangGraph · FastAPI · Next.js · pgvector · ECS Fargate · Terraform · GitHub Actions (OIDC) |
| [**post-ops-ai**](https://github.com/ajeya-krishna/post-ops-ai) | Drafts replies to LinkedIn comment threads under a fixed opinion standard. Comment text and linked repos are treated as untrusted input, and a human approves every reply. | Python · Claude API |
| [**Agentic OS**](https://github.com/ajeya-krishna/hackathon) | Voice-first planner that turns spoken thoughts into intentions, habits and a daily roadmap. | React · TypeScript · Llama 3 (Groq) · SQLite |
| [**LLAMA_2**](https://github.com/ajeya-krishna/LLAMA_2) | Clinical NLP with Llama-2-13B: entity extraction, retrieval and summarization over 5,000 clinical texts. | Llama 2 · LangChain · FAISS |
| [**Covid**](https://github.com/ajeya-krishna/Covid) | COVID-19 detection from X-ray and CT scans (99.7% accuracy on X-ray), plus U-Net infection segmentation. | ResNet50 · InceptionResNetV2 · U-Net |
| [**cascade_cup**](https://github.com/ajeya-krishna/cascade_cup) | Stacked-ensemble classifier for the DPhi Cascade Cup. Ranked **2nd of 251**. | scikit-learn |

### Tech stack

| Area | Tools |
|---|---|
| **LLMs & agents** | OpenAI · Claude · Llama · Hugging Face · PyTorch · LangChain · LangGraph · n8n · Langfuse |
| **Voice** | LiveKit · Twilio · Whisper · WebRTC · STT / TTS / VAD |
| **RAG & search** | Weaviate · Qdrant · Milvus · FAISS · Pinecone · pgvector · Elasticsearch |
| **Backend & infra** | Python · FastAPI · NestJS · PostgreSQL · MongoDB · Redis · Docker · Kubernetes · AWS · GCP · Terraform |

### Background

- IDD (B.Tech + M.Tech) in Engineering Physics, **IIT (BHU) Varanasi**, 2017–2022
- Rank **9 of 9,000+** in the IIT Guwahati ML Hackathon
- **Star Performer** and **Trail Blazer** awards at SaaS Labs

I also post engineering notes on LinkedIn about building AI systems in production: what broke, what I measured, and the trade-offs.
