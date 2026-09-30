<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Arnav Soni — AI/ML Engineer"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B0F24?style=for-the-badge&logo=linkedin&logoColor=22D3EE)](https://www.linkedin.com/in/arnav-soni-7a706b2b4)
[![Email](https://img.shields.io/badge/Email-0B0F24?style=for-the-badge&logo=gmail&logoColor=22D3EE)](mailto:soniarnav19@gmail.com)

</div>

<p align="center"><img src="./assets/sec-about.svg" width="100%" alt="About"/></p>

```python
arnav = {
    "role":       "AI/ML Developer",
    "university": "GGSIPU — B.Tech CSE '23–'27",
    "focus":      ["RAG", "LLM fine-tuning", "Agents", "Backend for AI"],
    "stack":      ["Python", "FastAPI", "PyTorch", "HuggingFace", "LangChain"],
}
```

<p align="center"><img src="./assets/sec-experience.svg" width="100%" alt="Experience"/></p>

<table>
<tr>
<td width="33%" valign="top">

**AI Developer Intern**
Desible.ai · Jul – Aug 2026

BERT intent classifier in a production voice-agent pipeline — routes generic intents to fixed responses, **cutting LLM calls**. Designed a **50-label taxonomy** across 4 domains; built an LLM labeling pipeline for Hindi/English code-switched transcripts → **~397K-row** training set.

</td>
<td width="33%" valign="top">

**AI Intern**
HCLTech (EPES AI Innovation) · Jan – Apr 2026

GenAI pipeline extracting & structuring data from **PDF contracts**. Benchmarked SARIMAX, Exp. Smoothing and Linear Regression on MAPE over 3–11 years — SARIMAX won at scale.

</td>
<td width="33%" valign="top">

**AI Developer Intern**
Jobeyze Limited, Canada · Jun – Aug 2025

AI immigration chatbot + top-3 job matching from a resume. Scrapy pipelines **re-crawl every 6 hours** and diff into a live PostgreSQL knowledge base. Async FastAPI + Celery + Redis, Dockerized.

</td>
</tr>
</table>

<p align="center"><img src="./assets/sec-projects.svg" width="100%" alt="Projects"/></p>

| Project | Stack | Result |
|---|---|---|
| **[BERT LoRA Fine-Tuning](https://github.com/Arnav-77/REPO)** | PyTorch · HuggingFace · LoRA from scratch · CI | ~95% of full fine-tuning accuracy (87.9% vs 92.7%) at 1.1% trainable params, ~38% less GPU memory. Warmup + early stopping took r=8 from 45% → 84%. |
| **[Stateful Research Agent](https://github.com/Arnav-77/REPO)** | Python · TF-IDF retrieval · rule-based grounding | 5-step retrieve → extract → draft → critique → revise loop, with an HTML trace viewer (latency, tokens, critic verdicts, diffs). |

<p align="center"><img src="./assets/lora-inference.svg" width="100%" alt="BERT-LoRA inference animation"/></p>

<details>
<summary><b>🔍 How setup beat rank in my LoRA sweep</b></summary>

<br>

At r=8, LoRA stalled at **45%** accuracy. Adding LR warmup + early stopping — with no change to rank — pushed it to **84%**. Takeaway: fix the training setup before tuning rank.

</details>

<details>
<summary><b>🧠 Research agent architecture</b></summary>

<br>

```mermaid
flowchart LR
  Q[Query] --> R[Retrieve<br/>TF-IDF] --> E[Extract] --> D[Draft] --> C{Critic:<br/>grounded?}
  C -- no --> V[Revise] --> C
  C -- yes --> A[Answer]
```

</details>

<p align="center"><img src="./assets/sec-stack.svg" width="100%" alt="Tech stack"/></p>

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-0B0F24?style=for-the-badge&logo=python&logoColor=C026D3)
![C++](https://img.shields.io/badge/C++-0B0F24?style=for-the-badge&logo=cplusplus&logoColor=C026D3)
![SQL](https://img.shields.io/badge/SQL-0B0F24?style=for-the-badge&logo=postgresql&logoColor=C026D3)

### ML / NLP
![PyTorch](https://img.shields.io/badge/PyTorch-0B0F24?style=for-the-badge&logo=pytorch&logoColor=A855F7)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-0B0F24?style=for-the-badge&logo=huggingface&logoColor=A855F7)
![BERT](https://img.shields.io/badge/BERT-0B0F24?style=for-the-badge&logoColor=A855F7)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0B0F24?style=for-the-badge&logoColor=A855F7)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0B0F24?style=for-the-badge&logo=scikitlearn&logoColor=A855F7)
![LangChain](https://img.shields.io/badge/LangChain-0B0F24?style=for-the-badge&logo=langchain&logoColor=A855F7)

### LLM APIs
![Gemini](https://img.shields.io/badge/Gemini-0B0F24?style=for-the-badge&logo=googlegemini&logoColor=7C5CFF)
![OpenAI API](https://img.shields.io/badge/OpenAI_compatible-0B0F24?style=for-the-badge&logo=openai&logoColor=7C5CFF)

### Backend & Infra
![FastAPI](https://img.shields.io/badge/FastAPI-0B0F24?style=for-the-badge&logo=fastapi&logoColor=60A5FA)
![Celery](https://img.shields.io/badge/Celery-0B0F24?style=for-the-badge&logo=celery&logoColor=60A5FA)
![Redis](https://img.shields.io/badge/Redis-0B0F24?style=for-the-badge&logo=redis&logoColor=60A5FA)
![Docker](https://img.shields.io/badge/Docker-0B0F24?style=for-the-badge&logo=docker&logoColor=60A5FA)
![AWS App Runner](https://img.shields.io/badge/AWS_App_Runner-0B0F24?style=for-the-badge&logo=amazonwebservices&logoColor=60A5FA)
![Scrapy](https://img.shields.io/badge/Scrapy-0B0F24?style=for-the-badge&logo=scrapy&logoColor=60A5FA)
![Git](https://img.shields.io/badge/Git-0B0F24?style=for-the-badge&logo=git&logoColor=60A5FA)

### Data & Vector Stores
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0B0F24?style=for-the-badge&logo=postgresql&logoColor=22D3EE)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-0B0F24?style=for-the-badge&logo=sqlalchemy&logoColor=22D3EE)
![Pinecone](https://img.shields.io/badge/Pinecone-0B0F24?style=for-the-badge&logoColor=22D3EE)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0B0F24?style=for-the-badge&logoColor=22D3EE)
![MinIO](https://img.shields.io/badge/MinIO-0B0F24?style=for-the-badge&logo=minio&logoColor=22D3EE)

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arnav-77/Arnav-77/output/github-snake-neon.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Arnav-77/Arnav-77/output/github-snake-neon.svg" />
</picture>

![Profile Views](https://komarev.com/ghpvc/?username=Arnav-77&color=7C5CFF&style=for-the-badge&label=PROFILE+VIEWS)

<img src="./assets/footer.svg" width="100%" alt="End of transmission"/>

</div>
