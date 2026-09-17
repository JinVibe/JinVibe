## Hi, I'm DongHyeon Jin 👋

CS undergrad at Kyungpook National University (GPA 4.29 / 4.5, major 4.37 / 4.5, graduating Feb 2027), heading toward ML research.
I care less about whether a model scores well and more about whether that score can be trusted —
calibration, evaluation noise, and reproducibility are the questions I keep coming back to.

🔭 **Currently**: small-LLM inference optimization · CTR calibration drift · applying to PhD programs (Fall 2027)

## 🔬 Research & ML

- **Small-LLM math reasoning** — Ajou Deep Learning Challenge 2026, **5th / 42 teams** with a frozen Qwen2.5-3B.
  93 experiments in a month. 9 fine-tuning attempts (SFT / GRPO / DPO / distillation) all hurt accuracy;
  decomposed via pass@k, found training was diluting majority voting, and shifted budget to
  confidence-weighted self-consistency (**+13.7%p over greedy**). Measured leaderboard noise (±0.48%p),
  pre-registered experiments, and reported 1,065 label errors to the organizers.
- **KSC 2025 paper** — *Exploring the Clusterability of Unclustered Embeddings: A Comparative Study of
  Embedding Models Based on Multi-Domain Multivariate Time Series Data* (co-first author).
- **CTR calibration drift** — Avazu (40M rows), DeepFM. Tracking how ECE degrades over time and
  whether post-hoc calibration survives distribution shift. *(in progress)*
- **Agentic dev loops** — shipped the iOS version of a dual-device camera app by designing an
  AI-agent implement → on-device verify → fix loop, with no prior Swift experience.

## 🛠️ Tech Stack

### 🧠 ML / LLM
<div>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
  <img src="https://img.shields.io/badge/vLLM-000000?style=for-the-badge">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white">
</div>

### ⚙️ Backend & Serving
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
</div>

### ☁️ Infra & MLOps
<div>
  <img src="https://img.shields.io/badge/Amazon%20AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white">
</div>

## 🚀 Selected Projects

| Project | What it is | My part |
|---|---|---|
| **Peakpic** (SW Maestro 17th) | Dual-device collaborative camera app — one phone shoots, the other frames | Android (Kotlin), WebRTC streaming optimization (low-light fps, VP9/H.264 negotiation, adaptive bitrate), AI-agent iOS port |
| **KNU Festival Service 2026** (LIKELION) | Campus festival platform, 13.7K active users in 5 days | PM & backend — Spring Boot, pre-computed matching + Redis cache for the 10 PM result spike, k6 load-tested, **106 RPS peak with zero downtime** |
| **Public-bid law-violation monitor** (DACON × PPS) | LLM pipeline that flags legal violations in procurement notices | Prompt / RAG / post-processing design *(in progress)* |
| **MCP-based AI search** (OSS Contest 2026) | Intelligent search over an MCP toolchain | Vector DB layer (PostgreSQL + pgvector) |

## 📊 GitHub Stats

![JinVibe's GitHub stats](https://github-stats-extended.vercel.app/api?username=JinVibe&theme=dark&show_icons=true)

## ✍️ Writing & Links

<div>
  <a href="https://velog.io/@loonaticvibe/posts"><img src="https://img.shields.io/badge/velog-20C997?style=for-the-badge&logo=velog&logoColor=white"></a>
  <a href="https://medium.com/@JinVibe"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/donghyeon-jin-42ab772a0/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:loonaticvibe2.11@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</div>
