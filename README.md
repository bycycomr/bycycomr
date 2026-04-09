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

I build **scalable backend systems and LLM-powered applications** across Java (Spring Boot), C# (.NET), and Python ecosystems. Currently working as an R&D Engineer at **Nurol Teknoloji**, where I own the AI backend of an enterprise NL2SQL platform — including RAG architecture, LangGraph agentic workflows, and FastAPI services.

I care about clean architecture, testable code, and solving real problems end-to-end.

---

## 🚀 Featured Projects

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
| 🏢 **Nurol Teknoloji** | R&D Engineer | Oct 2025 – Present |
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

## 🔬 In Progress

**Turkish Medical AI Assistant** — Fine-tuned LLM (Unsloth + LoRA) that maps colloquial Turkish patient language and regional dialects to standardized medical terminology. RAG integration planned to reduce hallucination rate.

---

<div align="center">

*Open to backend, AI/ML engineering, and full-stack roles — available from June 2026.*

</div>
