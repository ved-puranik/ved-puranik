<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=250&section=header&text=Ved%20Puranik&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Software%20Engineer%20%7C%20AI%2FML%20Engineer%20%7C%20Full%20Stack%20Developer&descAlignY=58&descAlign=50" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+production-grade+ML+%26+AI+systems;Shipping+apps+with+Next.js+%26+FastAPI;Architecting+RAG+and+agentic+workflows;Open+to+engineering+opportunities" alt="Typing SVG" />

<br/>

[![Education](https://img.shields.io/badge/UT%20Austin-B.S.%20Computer%20Science%20(In%20Progress)-6D28D9?style=for-the-badge&logo=googlescholar&logoColor=white)](#)
[![Location](https://img.shields.io/badge/Location-Austin%2C%20TX-7C3AED?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ved-puranik/)
[![Email](https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ved.puranik@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/user8997DZ/)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=ved-puranik&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/ved-puranik?style=for-the-badge&color=7C3AED&label=FOLLOWERS&logo=github)
![Stars](https://img.shields.io/github/stars/ved-puranik?style=for-the-badge&color=6D28D9&label=STARS&logo=github)

</div>

---

## ☞ About Me

<div align="center">

```yaml
name: "Ved Puranik"
role: "Software Engineer & AI/ML Engineer"
focus: "Building scalable, intelligent, production-grade systems"
philosophy: "Engineering thoughtful products at the intersection of software and AI"
```

</div>

I am a **Software Engineer** with a strong foundation in **full-stack development**, **applied AI/ML**, and **production system design**. My recent work spans machine learning pipelines for predictive analytics, retrieval-augmented generation (RAG) systems for privacy-sensitive domains, decentralized application architecture, and cross-platform mobile development.

I enjoy working across the entire stack — from designing ensemble ML models and RAG-based knowledge systems on the backend, to building polished, responsive interfaces with Next.js, React, and React Native on the frontend. My projects emphasize **production-readiness**: containerized deployments, evaluation-driven model selection, and privacy-first architecture where it matters most.

### 🎯 Open To

- 💼 Software Engineering roles (Full Stack / Backend / AI-ML)
- 🤝 Open Source collaborations
- 🚀 High-impact early-stage product teams
- 🧠 Applied AI/ML and RAG-focused engineering projects

---

## ☞ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,typescript,javascript,cpp&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css&theme=dark" />

**Backend, Mobile & Databases**

<img src="https://skillicons.dev/icons?i=nodejs,fastapi,supabase,postgres,react&theme=dark" />

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,vercel,vscode&theme=dark" />

</div>

---

## ☞ AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|---|:---:|---|
| **Machine Learning** | ⭐⭐⭐⭐⭐ | Ensemble modeling (Soft-Voting Classifiers, XGBoost, Random Forest), 5-fold stratified cross-validation, model evaluation |
| **NLP & LLMs / RAG** | ⭐⭐⭐⭐⭐ | Retrieval-augmented generation pipelines, local LLM inference (Ollama / Llama 3), grounded reasoning over private data |
| **Agentic AI Systems** | ⭐⭐⭐⭐ | Multi-agent pipelines for verification, semantic LLM evaluation, and orchestrated parallel execution |
| **Applied AI for Finance** | ⭐⭐⭐⭐ | AI-native market intelligence using LLMs over live news, social, and macro data |
| **MLOps & Deployment** | ⭐⭐⭐⭐ | Dockerized inference services, FastAPI model serving, locally-run privacy-first AI systems |

</div>

---

## ☞ Featured Projects

<details>
<summary><b>🏆 AI Predicts the 2026 FIFA World Cup</b></summary>
<br/>

An end-to-end, production-grade Machine Learning pipeline and Single Page Application predicting match outcomes for the 2026 FIFA World Cup using an ensemble stacking matrix.

| Aspect | Details |
|---|---|
| **Stack** | Python, FastAPI, XGBoost, Random Forest, Tailwind CSS |
| **Scale** | Pipeline evaluated across a ~1,000-row tournament dataset with full cross-validation |
| **Performance** | Soft-voting ensemble achieved 66% validation accuracy (peak 72.5%) via 5-fold stratified CV |
| **Security** | Asynchronous background prediction requests via FastAPI |
| **Impact** | Interactive dashboard lets users select any two qualified teams and view real-time, animated win/draw/loss probability distributions |
| **Repository** | [View Repository](https://github.com/ved-puranik/fifa-2026-world-cup-predictor) |

The model pipeline evolved through three phases — a baseline XGBoost classifier, a grid-searched tuned model evaluated with 5-fold cross-validation, and a final `VotingClassifier` combining XGBoost, Random Forest, and a third algorithmic approach in a soft-voting ensemble. The frontend is a modern Tailwind CSS SPA served directly via FastAPI, with dynamic team selection and animated outcome visualizations.

</details>

<details>
<summary><b>🩺 Medi-Diagnoser — Privacy-First AI Medical Scribe</b></summary>
<br/>

A production-grade, privacy-first AI medical scribe and knowledge-base system built to run entirely on local infrastructure — no patient data ever leaves the network.

| Aspect | Details |
|---|---|
| **Stack** | Python 3.11+, FastAPI, Next.js 16, TypeScript, Docker Compose, Ollama (Llama 3) |
| **Scale** | Full local pipeline: audio ingestion → transcription → redaction → structured note generation |
| **Performance** | Generates structured SOAP clinical notes and a searchable medical knowledge base from raw audio |
| **Security** | 100% local execution with redacted transcripts — designed for strict patient-data privacy |
| **Impact** | Converts patient-doctor audio recordings into redacted transcripts, structured clinical notes, and a queryable knowledge base |
| **Repository** | [View Repository](https://github.com/ved-puranik/rag-medical-diagnoser) |

Built as a fully containerized system (Docker Compose) combining a FastAPI backend, a Next.js/TypeScript frontend, and locally-hosted LLM inference via Ollama. The architecture is designed so that sensitive medical audio and transcripts never leave the user's own hardware, while still providing RAG-powered search over a structured knowledge base.

</details>

<details>
<summary><b>🪙 MediCoin — Decentralized Science Funding</b></summary>
<br/>

A decentralized science funding platform with agentic milestone verification, built at the Momentum Hackathon. Researchers tokenize IP as NFTs, fractionalize it into purchasable research tokens, and receive milestone-gated USDC disbursements verified by a multi-agent AI pipeline.

| Aspect | Details |
|---|---|
| **Stack** | TypeScript, Next.js, multi-agent LLM pipeline (Scraper, Verifier, Challenger, Orchestrator), SSE streaming |
| **Scale** | Multi-agent pipeline monitors live GitHub commits and research artifacts across demo research projects |
| **Performance** | Real-time verification via parallel agent execution and deliberation, streamed over SSE |
| **Security** | Milestone-gated fund release driven by automated, adversarial-reviewed AI verification rather than manual committee approval |
| **Impact** | Demo-scoped decentralized funding model with simulated on-chain execution and real agentic verification |
| **Repository** | [View Repository](https://github.com/ved-puranik/medicoin-science-funding) |

As **Blockchain & Smart Contract Architecture** lead on this hackathon team, contributions included the EscrowVault design, the IP-NFT fractionalization model, and the Base L2 deployment plan for the simulated on-chain execution layer, alongside a four-person team covering frontend, agent pipeline, and DeSci research.

</details>

<details>
<summary><b>📈 QuantShift — AI-Native Market Intelligence</b></summary>
<br/>

An AI-native market intelligence and trading companion that continuously ingests live market news and social/macro data, uses RAG over OpenAI models to build grounded market views, and maps those views to trade ideas tailored to a user's risk profile.

| Aspect | Details |
|---|---|
| **Stack** | Next.js 14 (App Router), TypeScript, Tailwind CSS, Supabase (Postgres + pgvector), OpenAI API |
| **Scale** | Designed to support per-user risk profiles (aggressive, moderate, patient, conservative) |
| **Performance** | RAG advisor route (`/api/advisor`) for grounded reasoning over market data and news embeddings |
| **Security** | Serverless API routes with Supabase-backed data layer |
| **Impact** | Starter architecture for an extensible AI trading-intelligence product, ready to deploy and extend |
| **Repository** | Private repository |

The system is architected around a Next.js + Supabase + OpenAI stack: Supabase stores user profiles, risk preferences, and document embeddings via pgvector for retrieval-augmented generation, while OpenAI's Chat Completions API powers reasoning and trade-idea generation.

</details>

<details>
<summary><b>📊 ksync — Business Tracker</b></summary>
<br/>

A cross-platform mobile business tracking app built with React Native and Expo, backed by Supabase.

| Aspect | Details |
|---|---|
| **Stack** | React Native, Expo, TypeScript, Supabase, React Navigation |
| **Scale** | Cross-platform support for iOS, Android, and Web via Expo |
| **Performance** | Native navigation with bottom tabs and stack navigators for smooth in-app transitions |
| **Security** | Supabase-backed authentication and data storage |
| **Impact** | Mobile-first business tracking workflow with location-aware features |
| **Repository** | Private repository |

Built on the Expo + React Native Web toolchain with `react-native-reanimated` and `react-native-gesture-handler` for fluid UI interactions, with Supabase providing the backend data layer and `expo-location` enabling location-aware tracking features.

</details>

---

## ☞ Experience

### Software Engineer — Add Company Name
**Add Date Range**

Add a professional description of your role and responsibilities here.

- Add scope-of-work bullet point
- Add scope-of-work bullet point
- Add scope-of-work bullet point

`Python` `TypeScript` `React` `FastAPI`

---

## ☞ Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 Momentum Hackathon | Built MediCoin — decentralized science funding platform with agentic milestone verification |
| 🌟 Open Source Contributor | Add details about your open source contributions |
| 🎓 Academic Excellence | Add your academic achievements |

</div>

---

## ☞ Coding Profiles

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/user8997DZ/)

</div>

---

## ☞ GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ved-puranik&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9&include_all_commits=true&count_private=true" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=ved-puranik&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ved-puranik&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" width="49%"/>

</div>

---

## ☞ GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=ved-puranik&theme=algolia&no-frame=true&no-bg=true&margin-w=10&column=4" />

</div>

---

## ☞ Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ved-puranik&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=A78BFA&line=8B5CF6&point=C9D1D9" width="100%"/>

</div>

---

## ☞ Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/ved-puranik/ved-puranik/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

---

## ☞ Current Focus

```yaml
current_focus:
  learning:
    - "Advanced RAG architectures and agentic AI workflows"
    - "Ensemble ML evaluation techniques"
    - "Cross-platform mobile development with Expo"

  building:
    - "Privacy-first AI systems (Medi-Diagnoser)"
    - "AI-native market intelligence tools (QuantShift)"
    - "Cross-platform business tracking apps (ksync)"

  exploring:
    - "Multi-agent orchestration for verification pipelines"
    - "On-chain integrations for decentralized platforms"

  open_to:
    - "Software Engineering roles"
    - "AI/ML Engineering roles"
    - "Open source collaborations"
```

---

## ☞ Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ved.puranik@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ved-puranik/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/user8997DZ/)

</div>

---

<div align="center">

*"Code is not just logic — it's the architecture of ideas brought to life."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
