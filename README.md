<div align="center">

# Hi, I'm Ömer Doğan 👋

**Backend Engineer · AI/LLM Systems · Full-Stack Developer**

*Computer Engineering student at Ankara University · Expected graduation June 2026*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/omer-dogan-bycycomr)
[![Portfolio](https://img.shields.io/badge/Portfolio-omerdogan.dev-111827?style=flat&logo=firefox&logoColor=white)](https://omerdogan.dev)
[![Medium](https://img.shields.io/badge/Medium-@bycycomr-000000?style=flat&logo=medium&logoColor=white)](https://medium.com/@bycycomr)
[![Email](https://img.shields.io/badge/Email-omerr.dogan11@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:omerr.dogan11@gmail.com)

</div>

---

I build **scalable backend systems and LLM-powered applications** across Java (Spring Boot), C# (.NET), and Python ecosystems. Currently a **Software Engineer (Mobile & AI)** at **Reading Health**, building a pregnancy-tracking app and researching AI models for teratogenicity risk prediction. Previously owned the AI backend of an enterprise **NL2SQL** platform at **Nurol Teknoloji** — RAG architecture, LangGraph agentic workflows, and FastAPI services.

I care about clean architecture, testable code, and solving real problems end-to-end. I also work on Turkish NLP as a side interest.

---

## 🚀 Featured Projects

### 🧹 [Yabay Zeka — Turkish AI-Text Pattern Cleaner](https://github.com/bycycomr/yabay-zeka) &nbsp;[![Stars](https://img.shields.io/github/stars/bycycomr/yabay-zeka?style=flat&label=%E2%AD%90)](https://github.com/bycycomr/yabay-zeka/stargazers)

> An open-source Claude/LLM skill that detects and strips AI-writing patterns from **Turkish** text — the bureaucratic suffixes, filler phrases, and hidden-subject constructions that make LLM output sound robotic.

- A ground-up **redesign** (not a translation) of the MIT-licensed [Stop Slop](https://github.com/hardikpandya/stop-slop) skill, built around Turkish-specific tells: `-mektedir/-maktadır` inflation, redundant `-dir` copula, "söz konusu / bağlamında / noktasında" filler, formulaic openers.
- Ships as an installable `.skill` package with reference files for banned phrases, structural clichés, and before/after transformations.
- Works with Claude Code, Claude Projects, custom instructions, and raw API system prompts.

---

### 🩺 TRMEDLLM — Turkish Medical LLM *(graduation project · publishing soon)*

> A fine-tuned Turkish medical language model that maps colloquial patient speech and regional dialects to standardized clinical terminology.

- **Base & method:** DeepSeek-R1-Distill-Qwen-14B, fine-tuned with **LoRA + Unsloth** on a purpose-built ~203K-record Turkish "patient statement → medical" dataset
- **Training:** 11,421 steps, ~79.5 hours on a single **RTX A4000**
- **Results:** CJK contamination cut from **82.2% → 0.3%**, clinical safety rate **91.3%**
- **Research output:** IEEE conference paper (submitted to ASYU 2026) · co-author Muhammed Emin Keçik · advisor Dr. Öğr. Üyesi Sevgi Yiğit Sert
- *Repository will be made public soon.*

---

### 🎫 [Tickly — Enterprise Help Desk & Ticket Management System](https://github.com/bycycomr/tickly)

> Full-stack help desk solution for corporate support teams — web + mobile, real-time, production-ready.

- **Backend:** ASP.NET Core 8 · C# · Entity Framework Core · SignalR · JWT Auth · SQLite/PostgreSQL
- **Frontend:** React 18 · TypeScript · TailwindCSS · React Query · Vite
- **Mobile:** Flutter 3 · Dart · Provider state management · Push notifications · Biometric auth
- Key features: SLA tracking, rule-based automation, real-time notifications, RBAC (Admin / Agent / EndUser), knowledge base, analytics dashboard
- 📺 [Web App Demo](https://www.youtube.com/watch?v=xCsViB2t8aw&t=1068s) · [Mobile App Demo](https://www.youtube.com/watch?v=DfSqHaIYX6Y)

---

### 🤖 [Dynamic Tool Selection Prototype — LangGraph AI Agent](https://github.com/bycycomr/Dynamic-Tool-Selection-Prototype)

> Zero-knowledge agent that decomposes complex multi-intent tasks and routes them to the right tools at runtime — no hardcoded schemas.

- **Stack:** Python · LangGraph · ChromaDB · sentence-transformers · pytest
- **Architecture highlights:**
  - **(A) Reflection loop** — on tool failure, re-searches and retries with error context injected (up to 2 retries)
  - **(B) Native LLM function calling** — structured JSON arguments via `bind_tools`, eliminates hallucinated args
  - **(C) Plan-and-Solve decomposition** — multi-intent tasks split into ordered sub-tasks
  - **(D) Hybrid search** — BM25 keyword scoring fused with ChromaDB vector similarity (0.6 × vector + 0.4 × BM25)
  - **(E) Stateful data flow** — tools run in dependency tiers; each output is injected as real context for downstream tools
- **47 passing tests** across graph flow, edge cases, planner, reflection, and hybrid search

---

### 🔍 [S4E QA Automation Suite](https://github.com/bycycomr/s4e-qa-automation-suite)

> Playwright + pytest automation suite covering login module security — happy paths, edge cases, and attack vector validation.

- **Stack:** Python · Playwright · pytest
- Covers: SQL injection, XSS, empty submission, long input, whitespace credentials
- Includes structured test case document, bug report, and shared fixture layer

---

## 💼 Experience

| | | |
|---|---|---|
| 🩺 **Reading Health** | Software Engineer — Mobile & AI (Flutter, .NET) | May 2026 – Present |
| R&D: building a pregnancy-tracking mobile app and researching AI models for teratogenicity risk prediction. | | Ankara |
| 🏢 **Nurol Teknoloji** | R&D Engineer | Oct 2025 – Apr 2026 |
| AI Backend owner for NL2SQL platform on InnovatioN Together. Built RAG architecture, LangGraph agentic workflows, and FastAPI services from scratch. | | Ankara |
| 🤖 **Intecro Robotics** | Junior Engineer (IT & Systems) | Apr 2025 – Oct 2025 |
| Linux/Windows server management, Bash/Python automation for backup/recovery, Active Directory RBAC & GPO configuration. | | Ankara |
| 💻 **Serebellum Bilişim** | Software Development Intern | Jul 2024 – Aug 2024 |
| React frontend development, backend integration, Git workflows, Linux deployment. | | Ankara |

---

## 🏆 Achievements

- 🥇 **DigiEduHack 2024 — Local Winner** · EU-backed international hackathon · Led team as full-stack lead on DigiCampus (EdTech platform)
- 🥈 **Ankü Game Jam 2024 — 2nd Place** · Built a 2D puzzle-platformer "Pink" from scratch in 48 hours with team leadership
- 🎓 **YAZGİT (Ankara University AI Society) — Vice President** · Organized Python & Data Science training for 250+ students, managed [yazgit.com](https://yazgit.com)
- 📚 **T3 Foundation Deneyap Workshops — AI Instructor** · 8-week ML & Python curriculum for middle school students

---

## 🛠️ Tech Stack

**Backend**
`Java` `Spring Boot` `C#` `.NET 8` `ASP.NET Core` `FastAPI` `RESTful APIs` `Clean Architecture`

**AI / LLM**
`Python` `LangGraph` `LangChain` `RAG` `LLM Fine-Tuning` `LoRA` `ChromaDB` `Unsloth`

**Frontend & Mobile**
`React` `TypeScript` `TailwindCSS` `Flutter` `Dart`

**Data & Databases**
`PostgreSQL` `SQLite` `MySQL` `Entity Framework` `Hibernate` `Pandas` `NumPy`

**DevOps & Tools**
`Docker` `Git` `GitHub Actions` `Linux` `Active Directory` `SignalR` `Swagger` `Agile/Scrum`

**Testing**
`pytest` `Playwright` `LangGraph test suite`

---

<div align="center">

*Open to backend, AI/ML engineering, and full-stack roles — available from June 2026.*

</div>
