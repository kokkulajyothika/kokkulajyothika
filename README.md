# Hi, I'm Jyothika 👋

**MSc Artificial Intelligence student at Teesside University (UK)** building AI agents and LLM automations that are **reliable, explainable and honest**: the AI classifies, the code verifies.

🎯 Looking for **AI Engineer / Applied AI / LLM engineering** internships and graduate roles in the UK.

---

## 🚀 Featured projects

### [Research Paper Assistant (RAG)](https://github.com/kokkulajyothika/Research-Paper-RAG-Assistant) · Python · PyTorch · RAG · [▶ Live demo](https://kokkulajyothika-research-paper-rag-assistant-app-gzdu8i.streamlit.app/)
Ask questions about 15 landmark AI papers and get answers where **every sentence cites a paper and page**, with the quote checked in code.
- Two-stage retrieval in PyTorch: bi-encoder search (all-MiniLM-L6-v2), then a cross-encoder reranker
- The reranker moved the correct paper to rank 1 for **17/17** answerable test questions (94% → 100% Recall@1); all 3 off-topic questions correctly refused
- Strict JSON citations from the LLM, quote verification that handles PDF quirks, retry with feedback, 16 unit tests, deployed on Streamlit

<a href="https://github.com/kokkulajyothika/Research-Paper-RAG-Assistant"><img src="https://raw.githubusercontent.com/kokkulajyothika/Research-Paper-RAG-Assistant/main/docs/screenshots/answer.jpg" width="420" alt="Research Paper Assistant answer with a verified citation"></a>

### [AI Job Hunt Agent](https://github.com/kokkulajyothika/AI-Job-Hunt-Agent-n8n) · n8n · Groq · AI Agents
An agent that finds UK job adverts every morning, scores them against a CV with **verified evidence quotes**, flags paid "training schemes" and senior roles, and writes tailored CVs and cover letters **without inventing skills**.
- Scoring calculated in JavaScript; every LLM quote is checked against the CV (hallucination check)
- Chat assistant with memory and 5 tools (find jobs, tailor CV, update status, agent health)
- Run log, error alerts, dashboard, weekly summary and an **accuracy test against human labels**: 84% rating agreement and 5/5 strong matches found on 19 labelled adverts

<a href="https://github.com/kokkulajyothika/AI-Job-Hunt-Agent-n8n"><img src="https://raw.githubusercontent.com/kokkulajyothika/AI-Job-Hunt-Agent-n8n/main/docs/screenshots/dashboard.jpg" width="420" alt="Job Hunt dashboard"></a>

### [AI CV Screening Assistant](https://github.com/kokkulajyothika/AI-CV-Screening-n8n) · n8n · Groq · REST API
Screens a CV against a job description and returns an evidence-based report through a web form and a JSON API.
- Weighted rubric scored in code, not by the LLM
- Hallucination check on every AI evidence quote; unverified quotes get half credit and are flagged
- PII anonymised before the CV reaches the LLM; same CV scored 82/100 across 3 repeated runs

<a href="https://github.com/kokkulajyothika/AI-CV-Screening-n8n"><img src="https://raw.githubusercontent.com/kokkulajyothika/AI-CV-Screening-n8n/main/docs/screenshots/form.jpg" width="300" alt="CV screening form"></a>

---

## 🛠️ Skills

**AI & LLMs:** LLMs · Generative AI · RAG (retrieval, reranking, cited answers) · AI Agents (tools + memory) · Prompt & Context Engineering · Structured Outputs (JSON Schema) · LLM Output Verification · LangChain · LangGraph · Groq API

**Automation, APIs & Deployment:** n8n · REST APIs · Webhooks · API integration · Docker · Streamlit · pytest

**Machine Learning:** PyTorch · sentence-transformers (embeddings, cross-encoders) · Deep Learning · CNNs · Computer Vision · TensorFlow · Scikit-learn · OpenCV

**Languages & Data:** Python · SQL · JavaScript · Java · Pandas · NumPy · MySQL · MongoDB · Git

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

---

## 🌱 Currently

- Studying Machine Learning, Deep Learning, NLP and Computer Vision (MSc AI, 2026–2028)
- Building and evaluating RAG systems; learning LLM evaluation and responsible AI

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/jyothikakokkula) · [kokkulajyothika@gmail.com](mailto:kokkulajyothika@gmail.com)
