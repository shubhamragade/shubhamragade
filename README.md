<div align="center">

# 👋 Hi, I'm Shubham Ragade

### AI/ML Engineer · Full-Stack Developer · MLOps Practitioner

*Building intelligent systems that solve real-world problems*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shubham-ragade-a9543531a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shubhamragade2003@gmail.com)
[![Medium](https://img.shields.io/badge/Medium-%23000000.svg?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@shubhamragade2003)
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ItAnivibe)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/)

</div>

---

## 🙋 About Me

```python
shubham = {
    "education"  : "BTech CSE — Deogiri Institute, Aurangabad (2021–2025)",
    "focus"      : ["LLMs", "Multi-Agent Systems", "RAG Pipelines", "MLOps", "Full-Stack AI Apps"],
    "experience" : ["AI/ML Intern @ Mhaske Technologies", "AI Intern @ Edunet Foundation (AICTE)"],
    "currently"  : "Building ChatCommerce AI & exploring voice fine-tuning with Qwen3-TTS",
    "reach_me"   : "shubhamragade2003@gmail.com"
}
```

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| 🤖 **AI/ML Intern** | Mhaske Technologies Pvt. Ltd. — Aurangabad | Mar 2025 – Sep 2025 |
| 🎓 **AI Intern** | Edunet Foundation (AICTE) — Remote | Dec 2024 – Feb 2025 |
| 💻 **Freelance — Voter Data Extractor** | Coreline IT Solutions — Remote | Sep 2025 – Oct 2025 |

> At **Mhaske Technologies**: Delivered production ML pipelines (preprocessing → training → FastAPI deployment) and built a full construction management platform with React + Django.
>
> At **Edunet Foundation**: Implemented ML workflows, data preprocessing pipelines, and API integrations under mentorship.
>
> **Freelance**: Built an automated voter data extraction system using Azure AI Vision OCR + GPT-4 for Marathi PDFs, with a parallel batch-processing pipeline that cut processing time by **40%**.

---

## 🚀 Featured Projects

### 🧠 Production & End-to-End Systems

---

#### 🏥 [Present-OS: AI-Powered Personal Productivity Platform](https://github.com/shubhamragade/present-os)
> *Your AI-powered personal operating system*

A comprehensive productivity platform that boosted user efficiency by **80%** across email, meetings, research, finance, messaging, and calendar — all driven by context-aware AI decisions (energy + weather signals).

- 🤖 **Parent–Child Multi-Agent Architecture** with long-term memory + RAG (Pinecone) to eliminate context loss
- 🔍 **Web search tool-calling agents** for real-time grounded responses
- 🗣️ Integrated **TTS/STT** for voice-driven interaction
- 🔄 Full automation pipeline with LangGraph orchestration

`FastAPI` `React` `OpenAI` `LangChain` `LangGraph` `Pinecone` `RAG` `TTS/STT` `Python`

---

#### 💼 [CareOps: Business Operating System](https://github.com/shubhamragade/creops)
> *Operational health for salons, spas & clinics*

Unlike typical booking apps, CareOps acts as the **"Brain & Robot Employee"** of service businesses — directly linking bookings to physical inventory, staff roles, and automated communications.

**3 Core Workflows:**
- 📦 **Perfect Booking Flow** — Real-time inventory checks; auto-deducts stock on booking, fires low-stock alerts to the owner
- 👥 **Staff Start Flow** — Secure password generation, role-based access control, staff-only portal (`/staff`)
- 💌 **Retention Flow** — Background cron jobs auto-send "Thank You / Rate Us" emails after every visit

`Next.js 14` `React` `TailwindCSS` `Shadcn UI` `FastAPI` `PostgreSQL` `SQLModel` `Resend API` `Docker`

---

#### 🛒 [ChatCommerce AI](https://github.com/shubhamragade/present-os) *(Ongoing)*
> *AI sales assistant — one inbox, all channels*

Building a unified AI-powered sales assistant that handles WhatsApp, Email, and web chat simultaneously to automate follow-ups and increase conversions.

- ⚡ **FastAPI backend** with RAG (pgvector), WebSockets, and Razorpay payment integration
- 🔐 JWT authentication, Redis caching
- 📊 Real-time sales pipeline visibility

`Python` `FastAPI` `PostgreSQL (pgvector)` `Redis` `Groq LLM` `React.js` `WebSockets` `Razorpay`

---

### 🎤 AI / Voice / Agents

---

#### 🎙️ [Voice AI Conversation System — NexaNova](https://github.com/shubhamragade/voice_agent)
> *Real-time Voice AI with < 1.2s total loop latency*

A high-performance voice assistant with ChatGPT-like natural conversation flow.

| Metric | Value |
|--------|-------|
| STT Latency | ~300ms |
| LLM Thinking | ~200ms |
| TTS Synthesis | ~150ms |
| **Total Loop** | **< 1.2s** |

- 🧠 **Smart transcript grouping** with 1s silence fallback — no cut-offs mid-sentence
- 📚 **Robust RAG Pipeline** — dynamic FAISS indexing of PDFs, TXT, DOCX with phonetic STT correction
- ⚡ **Instant interruption** via client-side Voice Activity Detection (VAD)
- 🔌 Session-synchronized WebSockets to prevent idle timeouts

`Python` `FastAPI` `OpenAI` `Deepgram` `FAISS` `LangChain` `WebSockets` `VAD`

---

#### 🗣️ [Hindi Voice Fine-Tuning & Cloning — Qwen3-TTS](https://github.com/shubhamragade/qwen-fine-tunned-repo)
> *Production-grade Hindi TTS on TPU*

End-to-end Hindi voice fine-tuning and cloning system trained on **TPU (v5e-1)** for high-quality speech synthesis. Includes dataset preparation, full fine-tuning pipeline, config debugging, and upstream contributions.

`Python` `PyTorch` `Qwen3-TTS` `Audio Codecs` `TPU v5e-1` `Model Fine-Tuning` `Inference Optimisation`

---

#### 📊 [AI Data Tooling MVP — SQL + RAG Agent](https://github.com/shubhamragade/SQL_RAG_AGENT)
> *Ask your database and documents in plain English*

Full-stack AI tooling app with **smart routing** between two agents:
- 🔍 **RAG Agent** — Query uploaded PDFs/TXT/DOCX via FAISS vector search
- 🗄️ **SQL Agent** — Natural language → validated, read-only MySQL queries
- 📈 Output formats: Text, sortable tables, interactive charts (Recharts)
- 🛡️ SQL safety layer blocks any destructive operations

`React` `TypeScript` `FastAPI` `Azure OpenAI (GPT-4)` `FAISS` `MySQL` `LangChain` `Recharts`

---

### 🏥 Healthcare AI

---

#### 🏥 [Post-Discharge Medical AI Assistant](https://github.com/shubhamragade/Post-Discharge-ai-assitence)
> *Multi-agent healthcare system for post-hospital support*

Intelligent system supporting patients after discharge via RAG + real-time medical web search.

**Multi-Agent Design:**
| Agent | Role |
|-------|------|
| 🤝 Receptionist Agent | Greets, verifies patient ID, routes medical queries |
| 🩺 Clinical Agent | Answers via RAG; falls back to DuckDuckGo web search |
| 🧠 Agent Manager | Controls flow, maintains state |

- 📚 Indexed *Comprehensive Clinical Nephrology* PDF into ChromaDB
- 🌍 Real-time web search when RAG confidence is low
- 📝 Full JSON audit logs for every interaction

`LangChain` `ChromaDB` `Groq (Llama-3.1)` `FastAPI` `Streamlit` `sentence-transformers` `DuckDuckGo Search`

---

### 📈 Trading & FinTech

---

#### 📉 [Binance Alpha — AI Trading Terminal](https://github.com/shubhamragade/trading-bot)
> *Conversational trading bot for Binance Futures Testnet*

Recruiter-ready trading bot demonstrating advanced Python, FinTech, and AI engineering.

- 🦾 **AI Chatbot Interface** — Natural language trading commands ("Go long 0.002 BTC", "Stop limit buy...")
- 🔐 **Zero-Library API Client** — Manual HMAC-SHA256 signing (no SDK dependency)
- 🌐 **Distributed Architecture** — FastAPI backend + Streamlit frontend
- 📉 **Real-time telemetry** — Live BTC price + USDT balance via REST polling
- 🛡️ **Triple-layer validation** — Pydantic + pre-API logic + exchange error handling
- 🧪 **Safe Demo Mode** — Full UI walkthrough without real API keys

`FastAPI` `Streamlit` `HMAC-SHA256` `Binance Futures API` `Python` `Pydantic` `Structured Logging`

---

### 🛠️ Tools & Automation

---

#### 📅 [Interview Scheduler Backend API](https://github.com/shubhamragade/interview_scheduler)
> *FastAPI service for scheduling interviews with auto email notifications*

Clean REST API for managing interview appointments with automatic email dispatch to candidates and interviewers. Async SQLAlchemy, CORS-ready, Swagger UI included.

`FastAPI` `SQLAlchemy (Async)` `SQLite` `Gmail SMTP` `Python` `Pydantic`

---

#### 🔍 [Demand Forecasting — Food Fulfillment Centers](https://github.com/shubhamragade/Demand-Forecasting-Project)
> *Predict future meal demand with a modern web UI*

Predicts meal demand at fulfillment centers using historical data and a Bootstrap 5 web interface.

`FastAPI` `Bootstrap 5` `Pandas` `Jinja2` `Uvicorn`

---

#### 🏦 [Risk Analytics in Banking & Financial Services](https://github.com/shubhamragade/Risk-Analytics-in-Banking-and-Financial-Services)
> *ML-based financial risk identification & mitigation*

End-to-end risk analytics project with EDA, ML modeling, and an interactive Flask dashboard.

`Pandas` `Seaborn` `Matplotlib` `scikit-learn` `Flask` `Jupyter`

---

#### 🧭 [Local Services RAG Assistant](https://github.com/shubhamragade/local-services-finder-RAG-based)
> *Find nearby electricians, plumbers & services via semantic search*

RAG-based assistant using embeddings and LLMs to surface local service providers from unstructured data.

`LangChain` `ChromaDB` `HuggingFace` `ChatGroq` `Python`

---

#### 🧠 [Face Recognition Intruder Alert System](https://github.com/shubhamragade/Intrusion-Detection-Using-Face-Recogntion-System)
> *Real-time intruder detection with email alerts*

Detects unrecognized faces in real-time and automatically dispatches SMTP email alerts.

`OpenCV` `Python` `SMTP` `NumPy`

---

#### 📊 [DDR — Dynamic Data Reporter](https://github.com/shubhamragade/DDR)
> *Streamlit-powered data reporting & visualization app*

`Python` `Streamlit`

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### AI / ML / LLMs
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### Frameworks & APIs
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

### MLOps & DevOps
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-%2312100E.svg?style=for-the-badge&logo=mlflow&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

### Databases & Vector Stores
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

---

## 🏆 Certifications

| Certificate | Issuer |
|-------------|--------|
| 📊 Data Analytics Certificate | Google |
| ☁️ AWS Cloud Architecting Graduate | AWS Academy |
| 🐍 Python for Data Science | IBM / CognitiveClass.ai |
| 📈 Career Essentials in Data Analysis | Microsoft |
| 🤔 Ask Questions to Make Data-Driven Decisions | Google / Coursera |

---

## 📊 GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=shubhamragade&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Streak](https://nirzak-streak-stats.vercel.app/?user=shubhamragade&theme=tokyonight&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shubhamragade&theme=tokyonight&hide_border=true&layout=compact)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=shubhamragade&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4)

</div>

---

<div align="center">

*"Building bridges between AI research and real-world impact."*

[![Profile Views](https://visitcount.itsvg.in/api?id=shubhamragade&icon=6&color=6)](https://visitcount.itsvg.in)

</div>
