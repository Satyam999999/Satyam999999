<div align="center">

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=F2A65A&center=true&vCenter=true&width=700&lines=Building+AI+Systems+That+Prove+Themselves+%F0%9F%A7%A0;RAG+%E2%80%A2+Agentic+AI+%E2%80%A2+LLMs;Evaluation-First+%E2%80%A2+Not+Just+Demos;Retrieval+%E2%80%A2+Fine-Tuning+%E2%80%A2+Deployment;Open+to+AI%2FML+and+Backend+Internships+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- Badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Satyam_Ghosh-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satyam-ghosh-43b81a290)
[![Email](https://img.shields.io/badge/Email-satyamghoshai12@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:satyamghoshai12@gmail.com)


<br/>

</div>

---

## ⚡ Who Am I?

```python
satyam = {
    "role"        : "Aspiring AI / ML Engineer",
    "education"   : "B.Tech CSE @ IIITDM Jabalpur (2023–2027)",
    "location"    : "Jabalpur, India 🇮🇳",
    "specializes" : ["RAG Systems", "NLP Classification", "Model Evaluation",
                     "Computer Vision", "Backend APIs"],
    "stack"       : ["Python", "PyTorch", "FastAPI", "LangGraph",
                     "Hugging Face", "Docker", "AWS/Azure"],
    "achievements": [
        "🏆 Amazon ML Summer School 2025 — Top 3,000 / 100,000+ students",
        "🥇 Amazon ML Challenge — Top 500 / 9,000+ teams"
    ],
    "currently"   : "Building evaluated AI systems & looking for a 6-month AI/ML or backend internship"
}
```

> *I don't call a model finished until I've measured it. Every project below reports what was measured, including where the result was not a win.*

---

## 🏆 Achievements at a Glance

<div align="center">

| 🏅 Achievement | 📊 Scale | 🎯 Result |
|---|---|---|
| Amazon ML Summer School 2025 | 100,000+ applicants nationwide | **Top 3,000 selected** |
| Amazon ML Challenge | 9,000+ competing teams | **Top 500 teams** |
| LeetCode | C++ | **Max rating 1827, best rank 2,764** |

</div>

---

## 🚀 Featured Projects

### 🧠 AskMyNotes — Retrieval-Augmented Generation System

> **Upload any PDF, ask anything, get cited answers — with an evaluation that reports what did and did not improve.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/AskMyNotes)

**Engineering highlights:**
- 🔍 **Hybrid retrieval** — dense (BGE) + sparse (SPLADE) embeddings fused via Reciprocal Rank Fusion, re-ranked with a local FlashRank cross-encoder
- 📊 **Measured, not assumed** — RAGAS on a 40-question golden set with a pinned judge, paired Wilcoxon tests, Holm correction and bootstrap CIs. Faithfulness **0.86 vs 0.76** for a dense-only baseline (95% CI +0.02 to +0.18, borderline after correction); no reliable difference in answer relevancy or context recall
- ⏱️ **Latency benchmarked honestly** — end-to-end median 4.6 s vs 2.0 s for dense-only (n=35); the extra time comes from reranking and longer cited answers
- 🌐 **Multilingual Q&A** — answers in English or Japanese, with exact page citations and eight study modes

```
Stack: Python · FastAPI · React · Qdrant · Groq LLM · RAGAS · LangSmith
```

---

### ⚖️ LegalMind — Contract Clause Risk Classifier

> **Fine-tuned Legal-BERT, compared against a LightGBM baseline and a majority-class baseline on a held-out test set.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/LegalMind-Intelligent-Risk-Analyzer)

**Engineering highlights:**
- 📈 **94.1% accuracy** (weighted F1 0.941) on 1,302 held-out clauses, vs 86.9% for Optuna-tuned LightGBM on Legal-BERT embeddings and 43.9% for a majority-class baseline
- 🧹 **Data cleaning** — CUAD extraction fixed and deduplicated (10,096 raw clauses to 8,679 unique)
- 🏷️ **Honest labelling** — risk tiers (High/Medium/Low) are mapped from CUAD clause categories
- 🖥️ **Full app** — upload a contract PDF, see the top 10 riskiest clauses and Gemini/Groq rewrite suggestions; Dockerized

```
Stack: Python · PyTorch · Hugging Face · LightGBM · Optuna · Streamlit · Docker
```

---


### 🗃️ Chat with Structured Data — Natural-Language-to-SQL Tool

> **Ask your database a question in plain English — with SQL checked before it runs.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Chat-with-Structured-Data)

**Engineering highlights:**
- 🗂️ **Normalized (3NF) schema** — Python ETL pipeline cleaning and structuring raw data before load
- 🛡️ **Safety-checked queries** — LLM-generated SQL is validated as read-only before execution, with automatic retry on failure
- 🖥️ **Full app, not a script** — Streamlit UI with generated SQL and results, containerized with Docker

```
Stack: Python · SQLite · Groq LLM · Streamlit · Docker
```

---

### 🎥 Brand Guardian AI — Multimodal Compliance Auditing System

> **Automates video compliance review — grounded in evidence, not a black-box score.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Multimodal-Video-Compliance-Auditor-using-LangGraph-Azure-Video-Indexer-and-RAG)

**Engineering highlights:**
- 🎙️ **Multimodal pipeline** — speech and on-screen text from Azure Video Indexer, retrieval over a 37-chunk policy index, and an LLM verdict in one two-node LangGraph workflow
- 📋 **Traceable verdicts** — hybrid retrieval over the compliance corpus delivering policy-grounded PASS/FAIL reports with severity-rated violations
- 🧩 **Schema-constrained outputs** — structured JSON reports, not free-form generation
- 📡 **Observable** — FastAPI `/audit` endpoint and CLI, instrumented with OpenTelemetry tracing to Azure Monitor

```
Stack: Python · FastAPI · LangGraph · Groq · Azure AI Search · Azure Video Indexer
```

---

### 🌱 Crop Disease Detection — Computer Vision Classifier

> **Benchmarked six architectures before trusting one.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Crop-Disease-Detection-Classification-Application)

**Engineering highlights:**
- 🧪 **Systematic model selection** — ANN, custom CNN, VGG16, ResNet50, EfficientNetB3 and DenseNet121 compared before fine-tuning ResNet50
- 📊 **85.62% test accuracy** across 22 disease categories (cashew, cassava, maize, tomato)
- 🎯 **Overfitting controls** — L2 regularization, dropout and augmentation with two-stage fine-tuning
- 📱 **Usable app** — Streamlit app giving a diagnosis and Gemini-generated treatment guidance from an uploaded photo

```
Stack: Python · TensorFlow/Keras · ResNet50 · Streamlit · Gemini API
```

---

### 📡 Environmental Sensor Anomaly Detection & Dashboard

> **A full year of real USGS sensor data, real anomalies, and a real Power BI dashboard.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Environmental-Sensor-Anomaly-Detection-Dashboard)

**Engineering highlights:**
- 🌊 **Real government data** — 34,677 readings (15-min intervals) pulled from the USGS NWIS API
- 🚨 **Evaluated detection** — rolling Z-score/IQR detectors checked against 5 manually annotated real events
- 📊 **Built dashboard, not just data prep** — interactive Power BI report: sensor filtering, time-series trends, anomaly table, KPI cards
- 🔎 **Honest reporting** — documented exactly where detection lagged (average time-to-alarm 645 minutes), not just the wins

```
Stack: Python · Pandas · NumPy · SciPy · Power BI · USGS NWIS API
```

---

## 🛠️ Tech Stack

### 🧠 Languages
<div align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp&theme=dark" height="50"/>
</div>

### 🤖 AI & Machine Learning
<div align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LightGBM](https://img.shields.io/badge/LightGBM-02A676?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6366F1?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-F2A65A?style=flat-square)

</div>

### 🗄️ Backend, Data & Cloud
<div align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,docker,aws,azure,git,github&theme=dark" height="50"/>
</div>

### 📈 Data & Visualization
<div align="center">

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</div>



## 🎯 Currently Focused On

```
◆ RAG & Retrieval Systems     — hybrid search, statistical evaluation (RAGAS), latency benchmarking
◆ NLP Model Fine-Tuning       — Hugging Face Transformers, evaluation against baselines
◆ Backend Services            — FastAPI, SQL data layers, Docker, tracing
◆ Deployment                  — Docker, AWS EC2, Azure
```

---

## 📫 Let's Build Something

<div align="center">

**Open to AI/ML and backend internships**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satyam-ghosh-43b81a290)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:satyamghoshai12@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore_my_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Satyam999999)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=footer" />

</div>
