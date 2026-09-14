<img src="assets/profile.jpg" align="right" width="185" alt="Venkata Srinivas" />

### Venkata Srinivas

I build the unglamorous infrastructure that makes AI features actually hold up in production — APIs, pipelines, guardrails, tests.

Right now I'm at **Arizona State University** finishing an **MS in Software Engineering** (Dec 2026). I also ship there: an LLM-powered grading platform that 5 professors run across 7 courses, handling 3,000+ submissions a semester. Before grad school I spent five years at Analytics Quad4 building demand-forecasting systems for 10,000+ SKUs on AWS.

[![Portfolio](https://img.shields.io/badge/Portfolio-0F0F0F?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR-PORTFOLIO-URL-HERE)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srinivas19/)
[![Google Scholar](https://img.shields.io/badge/Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=3ZER72AAAAAJ&hl=en)
[![Email](https://img.shields.io/badge/voguri@asu.edu-C8102E?style=flat-square&logo=gmail&logoColor=white)](mailto:voguri@asu.edu)

---

#### What I'm building

**DevContext — AI developer agent**
An autonomous agent on the Anthropic SDK and MCP that turns natural-language goals into multi-step work across 5 developer tools, pulling live GitHub and codebase context. Rebuilt it a second time on LangGraph + MCP with multi-server tool loading, streaming, and conversation memory — which cut the orchestration layer to about a quarter of the hand-rolled version. Bounded 8-turn execution, tool-call validation, and human approval before anything lands.

**[VisionCircadian](https://chromewebstore.google.com/search/VisionCircadian) — Chrome extension, live on the Web Store**
Computes your real-time Circadian Stimulation from what's actually on screen — melanopic weighting, sRGB-to-linear conversion, and published photobiological models rather than a generic blue-light slider. Exposure history persists in IndexedDB so the feedback is personal over time; 90% of users changed their display or theme settings because of it.

**Personalized ADAS in CARLA — MS thesis**
Reworking Forward Collision Warning and Adaptive Cruise Control state machines inside CARLA (Unreal Engine 4) so intervention timing adapts to the individual driver instead of a fixed threshold. A reinforcement learning loop in Python trains against the simulator's tick-based actor API using live telemetry. In user-in-the-loop playtests, manual overrides dropped 85% against a static baseline.

**Infi8 — Python library on PyPI**
A mathematical computation library, published and versioned (v0.1.2). Mostly an exercise in taking testing seriously: unit and regression suites over the core APIs, explicit edge-case and failure-path coverage, and a modular architecture that stays testable as it grows.

---

#### Published research

Machine learning for medical diagnosis — mostly interpretable, tree-based models on clinical data, chosen because a doctor has to be able to follow the reasoning.

- [**Parkinson's Disease Detection Using Tree-Based Machine Learning Algorithms**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=3ZER72AAAAAJ&citation_for_view=3ZER72AAAAAJ:u-x6o8ySG0sC) — *Current Trends in Biotechnology and Pharmacy*, 2023
- [**Automated Detection of Breast Cancer Using Machine Learning: A Comparative Analysis**](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=3ZER72AAAAAJ&citation_for_view=3ZER72AAAAAJ:u5HHmVD_uO8C) — 2022

---

#### Toolkit

| | |
|---|---|
| **Languages** | Python · JavaScript · Java · Swift · C/C++ · SQL · R |
| **Backend** | FastAPI · Flask · Node.js · PostgreSQL · Oracle · REST · OAuth 2.0 |
| **Frontend** | React · Material-UI · Chrome Extensions · IndexedDB |
| **AI & data** | Anthropic SDK · MCP · LangGraph · scikit-learn · PyCaret · TimeGPT · pandas · NumPy |
| **Infra** | Docker · AWS (S3, Lambda, ECS, RDS, Glue, Redshift) · GCP · GitHub Actions · CI/CD |

---

I teach the web applications course at ASU too — 60 students, and a fair amount of my week goes to debugging other people's async bugs and CORS errors in office hours. It has made me much better at reading unfamiliar code.

<p align="center">
  <img src="assets/photo-2.jpg" width="330" alt="" />
  <img src="assets/photo-3.jpg" width="330" alt="" />
</p>

**Open to Summer 2026 internships and new-grad roles** in backend, platform, or applied AI engineering. <a href="mailto:voguri@asu.edu">Say hi</a>.
