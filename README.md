<p align="center">
  <img src="./header.svg" width="100%" alt="Chinnawat Thongsuwan — AI Engineer" />
</p>

<p align="center">
  <a href="mailto:chinnawat.jayjay@gmail.com"><img src="https://img.shields.io/badge/Email-chinnawat.jayjay%40gmail.com-0f2a3a?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/chinnawat-thongsuwan-8b719434a"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://huggingface.co/chinnawat2424"><img src="https://img.shields.io/badge/Hugging%20Face-Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
</p>

---

## 👋 About Me

AI engineer working across **model development** and the **infrastructure that puts models into production**.

- 🤖 &nbsp;Built an **agentic RAG assistant** with a ReAct reasoning loop and four integrated tools on top of a Thai LLM
- ⚡ &nbsp;Optimized a **Vision Transformer** with ONNX INT8 quantization for a **73% latency reduction**, shipped through automated CI/CD
- 🐳 &nbsp;Administer **self-hosted Docker infrastructure** running production workloads for two business units
- 🎓 &nbsp;B.Eng. in Artificial Intelligence Engineering and Data Science, **Bangkok University** (2022 – 2026)

---

## 🚀 Featured Projects

### 📈 [Agentic RAG — Stock Investment Assistant](https://github.com/chinnawat2424/Agentic-RAG-Stock-Investment-Assistant)
<a href="https://huggingface.co/spaces/chinnawat2424/finfin"><img src="https://img.shields.io/badge/Live%20Demo-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Live demo" /></a>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/ChromaDB-Vector%20DB-0f2a3a?style=flat-square" alt="ChromaDB" />
<img src="https://img.shields.io/badge/Typhoon-v2.5%20LLM-145566?style=flat-square" alt="Typhoon LLM" />

- AI agent with a **ReAct reasoning loop** over the Typhoon v2.5 LLM, answering multi-step questions that combine retrieved context with live market data
- **Four agent tools:** semantic search over ChromaDB, live news retrieval, financial ratio calculation and real-time price lookup via yfinance
- Containerized Flask service on Hugging Face Spaces, with **multilingual embeddings** for Thai and English queries

### 🍜 [Food Vision API — MLOps Image Classification Service](https://github.com/chinnawat2424/food_ai)
<a href="https://huggingface.co/spaces/chinnawat2424/food_ai"><img src="https://img.shields.io/badge/Live%20Demo-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Live demo" /></a>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/ONNX-INT8-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" />
<img src="https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />

- Converted a **Vision Transformer** from PyTorch to ONNX with **INT8 quantization**: model size **−75%**, CPU latency **−73%**, accuracy loss **under 1%**
- Async **FastAPI** serving layer with ProcessPoolExecutor for CPU-bound inference and layered input validation
- Automated testing and deployment with **GitHub Actions** and **Docker**, load-tested with **Apache JMeter**

### 🧰 More Projects

| Project | Focus |
|:--|:--|
| [End-to-End MLOps Pipeline](https://github.com/chinnawat2424/End-to-End-MLOps-Pipeline-) | Machine-learning pipeline from training to deployment |
| [ML Model Deployment](https://github.com/chinnawat2424/ML-Model-Deployment) | Quantized ONNX model served via FastAPI, with pytest, Docker and GitHub Actions |
| [RAG](https://github.com/chinnawat2424/RAG) | Retrieval-augmented generation experiments in Python |

---

## 💼 Experience

**Engineering Intern — Siam Win Engineering and Supply Co., Ltd.** &nbsp;·&nbsp; *May – Jun 2026*

- Deployed and maintained a production web system on **self-hosted Docker**, with separate production and development environments
- Developed a full-stack Thai-language **quotation & BOQ system** (Next.js 14, Prisma, PostgreSQL) managing **5,700+ customers** and **5,300+ products** across two business units
- Built print-accurate A4 **PDF generation with Puppeteer**, including custom pagination and Thai typography
- Added revision history and per-user document numbering to keep quotation workflows auditable
- Administered a **Synology NAS** with a three-tier backup strategy for all company data
- Recovered legacy accounting data by **reverse-engineering** an obsolete proprietary database format in Python

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,pytorch,fastapi,flask,nextjs,react,nodejs&perline=9" alt="Languages and frameworks" />
  <br/>
  <img src="https://skillicons.dev/icons?i=prisma,postgres,mysql,sqlite,docker,githubactions,linux,git&perline=8" alt="Data and DevOps" />
</p>

| Area | Skills |
|:--|:--|
| **AI / ML** | LLM integration, Agentic RAG (ReAct), tool calling, ChromaDB, FAISS, embeddings, PyTorch, Vision Transformer, YOLO |
| **ML Serving & Optimization** | ONNX Runtime, INT8 quantization, FastAPI, async inference, model artifact management, Hugging Face Spaces |
| **Infrastructure & DevOps** | Docker, Docker Compose, GitHub Actions (CI/CD), Linux, Git, Git LFS, self-hosted deployment |
| **Testing & Performance** | pytest, Apache JMeter, load testing, latency profiling |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Databases** | PostgreSQL, MySQL, SQLite |
| **Frameworks** | FastAPI, Flask, Next.js, React, Node.js, Prisma ORM |

---

## 📜 Certifications & Activities

- 🏅 **Agentic AI with LangChain and LangGraph** — IBM, Coursera
- 🏅 **Transforming Exploratory Data Analysis with AI** — Coursera
- 🏅 **Creating Impactful Data Visualizations with Generative AI** — Coursera
- 🏅 **Microsoft Copilot for Power BI: AI-Powered Report Insights** — Coursera
- 🐘 **Technical Staff**, AI Hackathon: Elephant Identification 2025 — Bangkok University (Oct 2025)

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=chinnawat2424&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chinnawat2424&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top languages" />
</p>

<p align="center"><sub>Open to conversations about LLM applications, RAG and deploying ML to production.</sub></p>
