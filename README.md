<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey,%20I'm%20Arnav&fontSize=42&fontColor=fff&animation=blurOut&fontAlignY=32&desc=AI%2FML%20Developer%20%E2%80%A2%20RAG%20%E2%80%A2%20Fine-tuning%20%E2%80%A2%20Agents&descAlignY=55&descSize=14" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Building+RAG+pipelines+that+ship+to+production;LoRA+from+scratch%3A+95%25+accuracy+at+1.1%25+params;Agents+with+self-correcting+critic+loops" alt="Typing SVG"/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arnav-soni-7a706b2b4)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:soniarnav19@gmail.com)

</div>

---

## About Me

```python
arnav = {
    "role":       "AI/ML Developer",
    "university": "GGSIPU — B.Tech CSE '23–'27",
    "focus":      ["RAG", "LLM fine-tuning", "Agents", "Backend for AI"],
    "stack":      ["Python", "FastAPI", "PyTorch", "HuggingFace", "LangChain"],
}
```

---

## Experience

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

---

## Featured Projects

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

---

## Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### ML / NLP
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![BERT](https://img.shields.io/badge/BERT-4285F4?style=for-the-badge&logoColor=white)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-6366F1?style=for-the-badge&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### LLM APIs
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_compatible-412991?style=for-the-badge&logo=openai&logoColor=white)

### Backend & Infra
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS App Runner](https://img.shields.io/badge/AWS_App_Runner-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Scrapy](https://img.shields.io/badge/Scrapy-60A839?style=for-the-badge&logo=scrapy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Data & Vector Stores
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Arnav-77/Arnav-77/output/github-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Arnav-77/Arnav-77/output/github-snake.svg" />
</picture>

![Profile Views](https://komarev.com/ghpvc/?username=Arnav-77&color=6366F1&style=for-the-badge&label=PROFILE+VIEWS)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
