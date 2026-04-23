<div align="center">

<!-- ====================== HEADER ====================== -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=Rico%20Twesten-Weber&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Principal%20DevOps%20Engineer%20%7C%20adesso%20SE&descAlignY=58&descSize=18" width="100%" alt="header"/>

<!-- ====================== TYPING ANIMATION ====================== -->

<a href="https://ricotwesten.de">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&duration=3500&pause=800&color=0078D4&center=true&vCenter=true&width=720&lines=Infrastructure+should+build+itself.;Now+teaching+AI+to+run+the+pipelines.;Azure+%E2%9C%A6+Kubernetes+%E2%9C%A6+Terraform+%E2%9C%A6+GitOps" alt="Typing SVG" />
</a>

</div>

---

## Hi, I'm Rico Twesten-Weber👋

Principal DevOps Engineer at adesso SE. 15+ years of building cloud infrastructure, automation, and platforms. I move teams off manual, brittle ops and onto GitOps-driven platforms that mostly run themselves.

Lately I spend a lot of time wiring up AI to handle the DevOps work nobody wants to do by hand — incident triage, IaC reviews, that kind of thing.

---

## 🚀 What I'm Working On

- **🤖 AI Automation for DevOps:**
Trying to automate the boring parts of platform engineering. Terraform PR reviews, Kubernetes debugging, docs that write themselves. Hit or miss so far, but the hits are worth it.
- **☁️ Azure Platform Engineering:**
Internal developer platforms on Azure with Terraform, AKS, and GitOps. Dev teams get a clear path to production — security and compliance baked in, not bolted on.
- **🔄 GitOps at Scale:**
Multi-cluster Argo CD and Flux setups with progressive delivery and drift detection. `git push` as the single source of truth.
- **🎓 Mentoring & Knowledge Sharing:**
Helping engineers move into platform and SRE roles. Talking to people and sharing what I learnt.

---

## 🏆 Highlights

- 🥇 **Built GitOps platforms on AKS** that other client teams ended up copying as their baseline.
- 🤖 **Brought AI into DevOps workflows** — automated Terraform reviews, LLM-assisted on-call — cut MTTR by roughly 60%.
- 🛡️ **Wired policy-as-code** (OPA/Gatekeeper, Kyverno) into pipelines so misconfigs get caught before they hit prod.
- 📉 **Cloud cost optimization** with FinOps and IaC — clients saw real savings within the first quarter.
- 🎤 **Talk, write, and mentor** around DevOps, GitOps, and where AI fits into operations.

---

## 🔗 Project References

Projects I contributed to or helped shape as an idea partner.

### [MoE Sovereign](https://github.com/h3rb3rn/moe-sovereign) — Self-Hosted Multi-Model AI Orchestrator

> **Role:** Architecture · Feature Design · Use Cases

A production-grade, open-source AI orchestration platform that routes queries across local language models using a **Mixture-of-Experts** architecture — fully self-hosted, no cloud calls, no vendor lock-in.

**What makes it interesting from a DevOps/platform perspective:**
- 7-stage pipeline: semantic caching → planning → expert routing → MCP tools → GraphRAG → synthesis → knowledge ingestion
- VRAM-aware scheduling across inference nodes
- OpenAI- & Anthropic-compatible API — drop-in sovereign alternative to cloud AI providers
- One-line installer, Docker Compose / LXC / Kubernetes-ready

**Stack:** Python · Neo4j (GraphRAG) · ChromaDB · Valkey · Kafka · PostgreSQL · LangGraph · Docker

📄 [Docs](https://docs.moe-sovereign.org) · 🔗 [GitHub](https://github.com/h3rb3rn/moe-sovereign)

### [Scribably](https://github.com/rico-twe/scribably) — Browser-Native Voice Transcription & Prompt Pipeline

> **Role:** Architecture · Product Design · Full-Stack

A privacy-first, open-source transcription app that runs entirely in the browser — no backend, no server, no account required. Audio flows through a configurable three-stage pipeline (STT → clean → prompt), with every API call going directly from the browser to user-supplied keys (BYOK).

**What makes it interesting from a privacy/architecture perspective:**
- Zero-backend design: all state lives in localStorage / IndexedDB; no content ever touches a Scribably server
- Dual provider registry (STT + LLM) — swap Groq Whisper, OpenAI Whisper, Anthropic, or any OpenAI-compatible endpoint without changing app code
- On-device Whisper via WebGPU/WASM — 100% local transcription as an opt-in provider, no cloud call required
- Config exported as Base64 / QR code for zero-friction device transfer
- Browser extension with push-to-talk overlay — inserts transcribed text into any focused input field, system-wide
- Plugin API v2 with signed manifests and sandboxed Web Workers for community and pro plugins (voice → ticket, voice → commit, podcast pack, IDE dictation bridge)

**Stack:** React · TypeScript · Vite · Groq Whisper · OpenAI Whisper · Anthropic SDK · IndexedDB · Umami Analytics · Docker · Helm

📄 Docs · 🔗 GitHub

---

## 🎤 Let's Talk About

- 🚀 **DevOps & Platform Engineering**
- 🔄 **GitOps at Scale**
- 🤖 **AI Workflow Automation**
- ☸️ **Kubernetes in the Enterprise**
- 🌱 **Mentoring DevOps Newcomers**

---

## 🤝 Let's Connect

<div align="center">

Want to talk platform engineering, GitOps, or AI in ops? Or making the jump into DevOps? Reach out.  
**Best ways:**

<br/>

<a href="https://www.linkedin.com/in/rico-twesten-weber">
  <img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://ricotwesten.de">
  <img src="https://img.shields.io/badge/Visit%20My%20Site-1E88E5?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%" alt="footer"/>

<sub>⚡ <i>"Infrastructure should build itself."</i> · Last updated automatically · Made with ❤️ in Münster</sub>

</div>
