<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Devansh%20Chaudhary&fontSize=44&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Full%20Stack%20%26%20AI%20Engineer&descAlignY=55&descSize=18"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Building+distributed+systems+that+scale;Go+%7C+FastAPI+%7C+Next.js+%7C+Kafka+%7C+PostGIS;AI%2FML+%7C+LangGraph+%7C+PyTorch+%7C+TensorFlow;IIIT+Lucknow+%E2%80%94+CS+%26+Business" />

<br>

<a href="mailto:devanshc913@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/devansh-chaudhary-26ba73311/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/devansh-125"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://codeforces.com/profile/devanshc430"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/></a>
<a href="https://leetcode.com/u/devansh125/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>

</div>

<br>

## About Me

I'm a full-stack developer and AI/ML engineer who likes building systems that hold up under real load — event-driven backends, geospatial pipelines, and LLM-powered platforms, not just CRUD apps with a chatbot bolted on. Currently pursuing a **B.Tech in Computer Science and Business** at **IIIT Lucknow** (Expected 2028, CGPA 8.6/10).

Selected for **Amazon ML Summer School 2026** (top ~2% of 134,000+ applicants), and I spend my free time on competitive programming — 1000+ problems solved across Codeforces, CodeChef, and LeetCode.

- 🔭 Currently building **Sipra**, a real-time bio-logistics orchestration platform
- 🌱 Deepening my work with **Kafka, distributed systems, and LangGraph-based AI pipelines**
- ⚡ 99.35 percentile in JEE Main 2023 (top 0.65% of 1M+ candidates)

<br>

## Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**Languages**
<br>
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Backend & Streaming**
<br>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

</td>
<td valign="top" width="50%">

**AI / ML**
<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Frontend & Data**
<br>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-008000?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

</td>
</tr>
</table>

<br>

## Featured Projects

### 🚁 [Sipra — Autonomous Bio-Logistics Orchestrator](#)
`Go` `FastAPI` `Next.js` `PostGIS` `Redis` `Kafka`

A real-time platform for coordinating medical/bio-logistics deliveries with autonomous drone handoff.

- **B2B Webhook Fan-out** — Kafka-backed engine delivers HMAC-SHA256-signed corridor GeoJSON to partner fleets, committing offsets only after successful delivery so crashes redeliver instead of silently dropping.
- **AI Risk Monitor + Drone Handoff** — FastAPI ETA predictor (Google Routes + 5 residual factors) feeds a 6-rule decision engine; a Go state machine drives `InTransit → DroneHandoff` transitions on breach.
- **Spatial Corridor Engine** — Rolling 2km PostGIS exclusion corridor (`ST_MakeLine` + `ST_Buffer`) with versioned history and a post-commit hook that decouples broadcast from write latency.
- **Real-Time Ops** — Non-blocking WebSocket hub streaming 7 live event types with per-client drop semantics so slow clients never stall broadcasts.
- **Mission Control UI** — Next.js + Deck.gl dashboard with pulsing corridor overlays, live fleet swarm, and real-time AI risk scores on Google Maps.

---

### 🧠 [Eduverse — AI Tutoring Platform](#)
`FastAPI` `PostgreSQL` `LangGraph` `PGVector` `Nomic`

- **Context-Aware Architecture** — Built on LangGraph to orchestrate document workflows and multi-turn learning sessions, with OAuth for secure access.
- **Hybrid Search Pipeline** — Combines PGVector embeddings with PostgreSQL full-text search to deliver accurate, grounded answers from complex academic texts.
- **Persistent Session Memory** — Conversation summarization and session memory enable long-running tutoring sessions within LLM context limits.

---

### 📈 [FinAdvisor — AI-Powered Financial Advisor](#)
`Node.js` `Express` `MongoDB` `React` `OpenRouter`

- **AI Reasoning Pipeline** — GPT-4 Turbo via OpenRouter in a multi-layer pipeline for context-aware personal financial advice.
- **Financial Insights** — Expense categorization, trend detection, anomaly identification, and financial health metrics.
- **Secure APIs** — REST APIs with JWT auth, Google OAuth, and real-time AI responses.

> *Replace the `#` links above with your actual GitHub repo / live demo URLs.*

<br>

## Achievements

| | |
|---|---|
| 🏅 | **Amazon ML Summer School 2026** — top 3,000 of 134,000+ applicants nationwide (~2% acceptance) |
| 🌐 | **Open Source** — Super Contributor, Hacktoberfest 2025 (BuyMeACoffee-Africa, Vizit) |
| 🥇 | **Hackathons** — Global Finalist, Meta PyTorch Hackathon & HackoFiesta 6.1 (IIIT Lucknow) |
| 💻 | **Competitive Programming** — Codeforces Specialist (1472) · CodeChef 3★ (1741) · LeetCode Knight (1886) · 1000+ problems solved |
| 🎓 | **Academics** — 99.35 percentile, JEE Main 2023 (top 0.65% of 1M+ candidates) |

<br>

## Leadership

**Machine Learning Wing Member** — Google Developer Groups (GDG), IIIT Lucknow Chapter · *Aug 2025 – Present*
Delivered hands-on ML training to 200+ students.

<br>

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=devansh-125&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=devansh-125&layout=compact&theme=tokyonight&hide_border=true"/>

<br>

<img width="70%" src="https://streak-stats.demolab.com?user=devansh-125&theme=tokyonight&hide_border=true" />

</div>

<br>

<div align="center">

### Let's Connect

<a href="mailto:devanshc913@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/devansh-chaudhary-26ba73311/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/devansh-125"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=devansh-125&label=Profile%20Views&color=00D9FF&style=flat" />
<img src="https://img.shields.io/github/followers/devansh-125?label=Followers&style=social" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer"/>

</div>
