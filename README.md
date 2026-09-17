<div align="center">
<img align="center" src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTQxYzk2NjZlMWY4MWMyODA2MGRiNmM0YmI1MGM4NzAxOTdhMDZjYiZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PXM/ReybRIkRX6lGurRASE/giphy.gif" width="200px">
<h2 align="center">Hello! I'm Pedro Landolt</h2>
</div>
<br>

**Software Engineer — Security & AI.** MSc in Software Engineering from the [Faculty of Engineering, University of Porto](https://sigarra.up.pt/feup/pt/web_page.inicial) (17/20), with a thesis (18/20) on adversarial attacks against LLM-based code review. I work at the intersection of **application security and AI** — from LLM red-teaming and adversarial ML to vulnerability management and backend platforms. I like understanding how systems fail and making them harder to break.

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=PedroLandolt&show_icons=true&theme=onedark&include_all_commits=false&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PedroLandolt&layout=compact&langs_count=7&theme=onedark"/>
</div>

<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/LangChain%2FLangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/C%23%2F.NET-512BD4?style=flat&logo=dotnet&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Security-red?style=flat&logo=hackthebox&logoColor=white">
</p>

<h2 align="center">Projects</h2>

### VULMAN — Vulnerability management platform · [vulman](https://github.com/PedroLandolt/vulman)
Full-stack platform built end to end: ETL pipelines aggregating threat intel (CISA KEV, NVD, EPSS, VulnCheck), asset–vulnerability correlation, risk scoring, LLM-based remediation, and REST integrations (Jira, GitHub).
`Python` · `ETL` · `PostgreSQL` · `LLM` · `REST APIs`

### Portline Invoice Processor · [InvProcess](https://github.com/PedroLandolt/InvProcess)
Automated invoice processing for a logistics company: PDFs are extracted, validated against ERP vendor data, stored, and submitted to the ERP API — a full pipeline behind a role-based finance dashboard. FastAPI backend (extraction, validation, ERP integration, JWT auth) with a Vite/React frontend.
`Python` · `FastAPI` · `React` · `ETL` · `PDF extraction`

### Robot Operator UI · [RobotOperatorUI](https://github.com/PedroLandolt/RobotOperatorUI)
Operator dashboard for supervising a greenhouse spraying robot. The robot streams telemetry over WebSocket, and the UI treats connection state as a first-class safety concern, so the operator always knows whether the data is live. Mission state machine, real-time push, a robot simulator, and 138 tests across a TypeScript monorepo.
`TypeScript` · `React` · `WebSockets` · `real-time` · `testing`

### LangGraph Challenge (Devoteam) · [devoteam-challenge](https://github.com/PedroLandolt/devoteam-challenge)
<!-- TODO: 1 linha real sobre o que faz — ex.: "Agentic workflow built with LangGraph that <faz X> using <Y>." -->
Agent/orchestration workflow built with **LangChain/LangGraph**.
`Python` · `LangGraph` · `LLM agents`

<h2 align="center">Master's Projects (MESW)</h2>

### JESTER — Adversarial attacks on code LLMs · [repo](https://github.com/PedroLandolt/Adversarial_Attacks_on_Code_Large_Language_Models_Using_Reinforcement_Learning)
**J**udge **E**valuation via **S**elective **T**actic-based **E**xploit **R**einforcement. Black-box attack framework (MSc thesis, 18/20) that drives an LLM code-review judge to approve code that is *provably* wrong — an attempt only counts when the deterministic tests **fail** and the judge returns **PASS**. Built on multi-armed bandits (UCB1, Thompson Sampling, KL-UCB, EXP3), it reached **67.6% first-attempt attack success — double the random baseline**. Dataset published on [HuggingFace](https://huggingface.co/datasets/PedroLandolt/adversarial-code-buggy); full dissertation PDF included in the repo.
`Python` · `LLMs` · `adversarial ML` · `reinforcement learning`

<h2 align="center">Bachelor's Projects (LEIC)</h2>

| UC   | Name      | Description                                                                                                                                                   | Grade (/20) |
|------|-----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| PI   | [VIAVERDE](https://github.com/PedroLandolt/PI-VIAVERDE)  | Internship: integration of a ViaVerde expense system | 19 |
| FSI  | [Logbooks & CTFs](https://github.com/PedroLandolt/FSI)  | Offensive-security logbooks and CTF write-ups | 20 |
| DA   | [SolvingTSP](https://github.com/PedroLandolt/SolvingTSP)  | Solving TSP with different algorithms, exact and approximate solutions | 20 |
| LBAW | [RedHot](https://github.com/PedroLandolt/RedHot)  | Full online store — focus on web development and database design | 19.5 |
| ES   | [TeachMeWell](https://github.com/PedroLandolt/TeachMeWell)  | An app to rate University of Porto professors and help students pick their classes | 19.3 |
| AED  | [LeicPlan](https://github.com/PedroLandolt/LeicPlan)  | Student schedule management with class-balancing and a data-structure analyzer | 18.55 |
| PFL  | [Haskell](https://github.com/PedroLandolt/Coursework-Haskell)  | An assembler and a compiler + parser written in Haskell | 18.03 |
| LCOM | [DefendTheBase](https://github.com/PedroLandolt/DefendTheBase)  | Tower-defense game using all I/O devices (Timer, Keyboard, Mouse, RTC) | 18 |
| AED  | [AirMS](https://github.com/PedroLandolt/AirMS)  | Airline database management system in C++ using several data structures | 17.85 |
| LDTS | [TBL](https://github.com/PedroLandolt/TBL)  | The Binding of Lendêa — a roguelike game inspired by The Binding of Isaac | 18 |
| FP   | [Pirates](https://github.com/PedroLandolt/Pirates)  | A Mario-style platformer where you fight your way to the treasure | 17.4 |
| DA   | [RailwayMS](https://github.com/PedroLandolt/RailwayMS)  | Route and connection optimization for a travel agency | 17.2 |
| LTW  | [PourProblems](https://github.com/PedroLandolt/PourProblems)  | A platform for users to share wine-related experiences and issues | 16.4 |

<h2 align="center">Contact me</h2>
<p align="center">
<a href="mailto:pedrolandolt88@gmail.com"><img title="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/pedrolandolt"><img title="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://huggingface.co/PedroLandolt"><img title="HuggingFace" src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
</p>
