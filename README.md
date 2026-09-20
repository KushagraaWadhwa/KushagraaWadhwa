<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Kushagra%20Wadhwa&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%2FML%20Software%20Engineer%20%7C%20Production-Grade%20GenAI%20Systems&descAlignY=55&descSize=16" />

</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=700&lines=RAG+Pipelines+%7C+Vector+Search+%7C+Agentic+AI;Fine-tuning+VLMs+%7C+QLoRA+%7C+Production+Deployment;I+build+AI+that+holds+up+past+the+demo)](https://git.io/typing-svg)

</div>

---

<h3 align="center">Most profiles hand you a bio. Mine answers a query.</h3>

```http
POST /v1/retrieve
Content-Type: application/json

{ "query": "who is this person, actually?", "top_k": 3 }
```

**`200 OK`** — 3 chunks retrieved, reranked by relevance:

| score | chunk | source |
|:--|:--|:--|
| `0.97` | Built production GenAI infra at **Shorthills AI** — RAG over enterprise document repositories, multimodal ingestion, vector search at 1M-object scale | `experience/shorthills.md` |
| `0.94` | Fine-tuned **Qwen2.5-VL-3B** (QLoRA, 4-bit NF4) to read handwritten prescriptions → structured JSON. Running in a live clinical deployment | `projects/patient-monitoring.md` |
| `0.91` | Now pursuing **M.Tech, AI & Data Science @ IIIT Bangalore** — going after the theory behind systems already shipped | `education/iiitb.md` |


> ⚠️ `grounding_check: PASSED` — every claim above traces to a source. That's the whole point.

---

## Tech Stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

**GenAI & LLMs**

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white" />
</p>

**Backend & APIs**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth2-3C873A?style=for-the-badge&logo=auth0&logoColor=white" />
</p>

**Data & Vector Stores**

<p>
  <img src="https://img.shields.io/badge/Weaviate-1D1D1D?style=for-the-badge&logo=weaviate&logoColor=green" />
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

**Agentic & DevOps**

<p>
  <img src="https://img.shields.io/badge/Google%20ADK-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-6C63FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
</p>

---

## Featured Projects

### AI-Powered Patient Monitoring System `https://kheeltechnologies.com/`
QLoRA-fine-tuned Qwen2.5-VL-3B (4-bit NF4, PEFT) reading real handwritten Indian prescriptions into structured JSON — medicines, dosage, frequency, instructions — wired into an async FastAPI backend serving live vitals across concurrent HD monitor streams. Actually deployed in a clinical environment.

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
</p>

[Model on Hugging Face](https://huggingface.co/KushagraWadhwa/medical-prescription-ocr-india)

### LLM-Powered Voice Sales Assistant
Whisper transcription → RAG over ChromaDB → grounded, hallucination-guarded answers, tuned end-to-end for ~1.2s response latency.

<p>
  <img src="https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
</p>

---

## Things I Learned The Expensive Way

<table>
<tr><td width="33%" valign="top">

**Benchmarks lie until you load-test**

A vector setup that looked healthy in dev had a hard concurrency ceiling far below what anyone assumed. Locust found it. Production didn't have to.

</td><td width="33%" valign="top">

**Chunking is the whole ballgame**

More context isn't better context. Most "the model is dumb" bugs turned out to be retrieval bugs wearing a costume.

</td><td width="33%" valign="top">

**"I don't know" is a feature**

Guardrails and structured output enforcement did more for trust than any prompt-tuning pass I ever ran.

</td></tr>
</table>

---

## Achievements

| | |
|---|---|
| 🎓 | **Google Agent Development Kit Certification** |
| 🎓 | **Diploma in Programming & Data Science** — IIT Madras |
| 🥇 | **GATE DA 2025 — AIR 663** |

---

## `CHANGELOG.md`

```diff
## [2026.09] - current
+ M.Tech @ IIIT Bangalore: convex optimization, advanced algorithms, DNNs from first principles
+ Digging into the math under the systems I'd already shipped on intuition

## [2026.07]
+ Wrapped up a year at Shorthills AI
+ Shipped: multimodal RAG ingestion, earnings-call intelligence, vector search benchmarking

## [2025.07]
+ Joined Shorthills AI as AI/ML Software Engineer

## [2025.05]
+ B.Tech, AI & ML — GGSIPU
```

---

## GitHub Stats

<div align="center">
<img height="165em" src="https://github-readme-stats.vercel.app/api?username=KushagraaWadhwa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KushagraaWadhwa&layout=compact&theme=tokyonight&hide_border=true" />
</div>

---

## Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/kushagrawadhwa263/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:wadhwakushagra263@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/KushagraaWadhwa" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://huggingface.co/KushagraWadhwa" target="_blank">
    <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge" />
  </a>
</p>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

*"A model that can't say 'I don't know' is more dangerous than one that's slow."*

</div>
