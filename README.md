<div align="center">

<!-- Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=800&color=F2A65A&center=true&vCenter=true&width=700&lines=Building+AI+Systems+That+Prove+Themselves+%F0%9F%A7%A0;RAG+%E2%80%A2+Agentic+AI+%E2%80%A2+LLMs;Evaluation-First+%E2%80%A2+Not+Just+Demos;Retrieval+%E2%80%A2+Fine-Tuning+%E2%80%A2+Deployment;Open+to+AI%2FML+Engineer+Roles+%F0%9F%9A%80" alt="Typing SVG" />
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
    "specializes" : ["RAG Systems", "Agentic AI", "LLM Fine-Tuning",
                     "Computer Vision", "Model Evaluation"],
    "stack"       : ["Python", "PyTorch", "FastAPI", "LangGraph",
                     "Hugging Face", "Docker", "AWS/GCP/Azure"],
    "achievements": [
        "🏆 Amazon ML Summer School 2025 — Top 3,000 / 100,000+ students",
        "🥇 Amazon ML Challenge — Top 500 / 9,000+ teams"
    ],
    "currently"   : "Shipping evaluated AI systems & targeting AI/ML roles in Japan 🇯🇵"
}
```

> *I don't call a model finished until I've measured it. Every project below ships with an evaluation, not just a demo.*

---

## 🏆 Achievements at a Glance

<div align="center">

| 🏅 Achievement | 📊 Scale | 🎯 Result |
|---|---|---|
| Amazon ML Summer School 2025 | 100,000+ applicants nationwide | **Top 3,000 selected** |
| Amazon ML Challenge | 9,000+ competing teams | **Top 500 teams** |
| LeetCode | Competitive programming | **1827 rating, rank 2,764** |

</div>

---

## 🚀 Featured Projects

### 🧠 AskMyNotes — Retrieval-Augmented Generation System

> **Upload any PDF, ask anything, get cited answers — with evaluation to prove it actually works.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/AskMyNotes)

**Engineering highlights:**
- 🔍 **Hybrid retrieval** — dense (BGE) + sparse (SPLADE) embeddings fused via Reciprocal Rank Fusion, re-ranked with a local FlashRank cross-encoder
- 📊 **Measured, not assumed** — RAGAS evaluation across two iterations: faithfulness 0.43→0.93, context recall 0.47→0.93
- ⚡ **Optimized end-to-end** — main Q&A latency cut from 19.0s to 2.9s
- 🌐 **Multilingual Q&A** — answers in English or Japanese, retrieval grounded in the source document's original language

```
Stack: Python · FastAPI · React · Qdrant · Groq LLM · RAGAS · LangSmith
```

---

### 🔬 Text Classification API — Fine-Tuned NLP Microservice

> **DistilBERT fine-tuned, evaluated against baseline, and shipped as a real deployed service.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Text-Classification-API)

**Engineering highlights:**
- 📈 **Proven improvement** — 26.0% zero-shot baseline → 88.4% accuracy, isolated via a dedicated `eval.py` script
- 🚀 **Real deployment** — Dockerized FastAPI service on AWS EC2, infrastructure auto-provisioned via a custom `boto3` script
- 📚 **Documented API** — interactive Swagger UI for testing and reproducibility

```
Stack: Python · PyTorch · Hugging Face Transformers · FastAPI · Docker · AWS
```

---

### 🗃️ Chat with Structured Data — Natural-Language-to-SQL Tool

> **Ask your database a question in plain English — safely, and with proof it works.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Chat-with-Structured-Data)

**Engineering highlights:**
- 🗂️ **Normalized (3NF) schema** — Python ETL pipeline cleaning and structuring raw data before load
- 🛡️ **Safety-checked queries** — LLM-generated SQL is validated before execution, with automatic retry on failure
- ✅ **Evaluation suite** — tested against real questions to confirm correctness, not assumed
- 🖥️ **Full app, not a script** — Streamlit UI with generated SQL, results, and auto-charts, containerized with Docker

```
Stack: Python · SQLite · Groq LLM · Streamlit · Docker
```

---

### 🎥 Brand Guardian AI — Multimodal Compliance Auditing System

> **Automates video compliance review — grounded in evidence, not a black-box score.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999)

**Engineering highlights:**
- 🎙️ **Multimodal pipeline** — STT + OCR + RAG + LLM reasoning fused into one grounded decision
- 📋 **Traceable verdicts** — hybrid retrieval over a 37-chunk compliance corpus delivering policy-grounded PASS/FAIL calls
- 🧩 **Deterministic outputs** — schema-constrained LangGraph workflows, not free-form generation
- 📡 **Fully observable** — instrumented with OpenTelemetry across every pipeline stage

```
Stack: Python · FastAPI · LangGraph · Groq · Azure AI Search · Azure Video Indexer
```

---

### 🌱 Crop Disease Detection — Computer Vision Classifier

> **Benchmarked 5 architectures before trusting one — accuracy backed by real experimentation.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999)

**Engineering highlights:**
- 🧪 **Systematic model selection** — 5 architectures benchmarked before fine-tuning ResNet50
- 📊 **Real improvement** — accuracy up from a 38% baseline to 85.62% across 22 disease categories
- 🎯 **Overfitting fixed with evidence** — L2 regularization + dropout on the top 10 fine-tuned layers
- 📱 **Deployed for real use** — Streamlit app giving instant diagnosis from an uploaded photo

```
Stack: Python · TensorFlow · ResNet50 · OpenCV · Streamlit
```

---

### 📡 Environmental Sensor Anomaly Detection & Dashboard

> **A full year of real USGS sensor data, real anomalies, and a real Power BI dashboard.**

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github)](https://github.com/Satyam999999/Environmental-Sensor-Anomaly-Detection-Dashboard)

**Engineering highlights:**
- 🌊 **Real government data** — 34,677 readings (15-min intervals) pulled live from the USGS NWIS API
- 🚨 **Validated detection** — rolling Z-score/IQR detectors caught a tropical storm turbidity spike instantly
- 📊 **Built dashboard, not just data prep** — interactive Power BI report: sensor filtering, time-series trends, anomaly table, KPI cards
- 🔎 **Honest reporting** — documented exactly where detection lagged, not just the wins

```
Stack: Python · Pandas · NumPy · SciPy · Power BI · USGS NWIS API
```

---

## 🛠️ Tech Stack

### 🧠 Languages
<div align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,c&theme=dark" height="50"/>
</div>

### 🤖 AI & Machine Learning
<div align="center">

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6366F1?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS-F2A65A?style=flat-square)

</div>

### 🗄️ Backend, Data & Cloud
<div align="center">
  <img src="https://skillicons.dev/icons?i=fastapi,flask,docker,aws,gcp,azure,postgres,git,github&theme=dark" height="50"/>
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
◆ RAG & Retrieval Systems     — hybrid search, evaluation (RAGAS), latency optimization
◆ Agentic AI                  — LangGraph, multi-agent orchestration (CrewAI)
◆ Model Fine-Tuning           — Hugging Face Transformers, evaluation against baseline
◆ Production Deployment       — FastAPI, Docker, AWS/GCP/Azure, CI/CD
```

---

## 📫 Let's Build Something

<div align="center">

**Open to AI/ML Engineer internships & full-time roles**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satyam-ghosh-43b81a290)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:satyamghoshai12@gmail.com)
[![GitHub](https://img.shields.io/badge/Explore_my_GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Satyam999999)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=footer" />

</div>
