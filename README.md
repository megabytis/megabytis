<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">

<h1 align="center">
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="32">
  Hey, I'm <b>Madhusudan Bhukta</b>
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="32">
</h1>

<p align="center">
  <b>Backend Engineer • Node.js, Express & AI Systems Architecture • Systems > CRUD • Always Shipping</b>
</p>

---

## ⚡ About Me
<img align="right" width="260" src="https://media.tenor.com/XP4tw9P1yFoAAAAM/dedsec.gif"/>

- Backend Engineer with hands-on production experience building REST APIs and cross-service communication layers.
- Specialized in **Node.js, Express, Python FastAPI, MongoDB, and Redis performance optimization**.
- Architecting **GenAI workflows** — LangGraph multi-agent state machines, RAG pipelines, ChromaDB vector search, and hybrid retrieval.
- Experienced in production deployments on **AWS EC2** with **Docker Compose, Nginx reverse proxying, and SSL encryption**.
- Empirical performance mindset: systematic load profiling with **k6** to locate database and compute saturation limits.
- Believe in shipping clean, defensible code → measuring real bottlenecks → scaling architecture.

<br>

## 🛠 Tech Stack

### **Languages**
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)

### **Backend & Infrastructure**
![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![ExpressJS](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)

### **GenAI & Vector Search**
![LangGraph](https://img.shields.io/badge/LangGraph-FF4F00?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-4A90E2?style=for-the-badge&logo=database&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### **Cloud & DevOps**
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![k6](https://img.shields.io/badge/k6_Load_Testing-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<br>

## 🚀 Featured Projects

### 🤖 **Project KYH — AI Fitness Agent (Flagship)**
**Multi-Agent Health Coach Deployed on AWS Cloud Infrastructure**

- Architected an asynchronous multi-agent health coach using **LangGraph**, orchestrating **7 discrete graph nodes** and specialized subgraphs to isolate food intake parsing from macro calculation logic.
- Containerized and orchestrated split Node.js communication gateway and Python AI execution runtimes via **Docker Compose**.
- Deployed directly to a dedicated **AWS EC2** instance with custom domain mapping (`kyh.bhuktatech.in`), Nginx reverse proxying, and SSL encryption (Certbot).
- Implemented multi-day user session persistence using LangGraph checkpointing layers synced with MongoDB Atlas to track and evaluate behavioral nutrition trends over a 30-day window.

<div style="margin-bottom: 1rem;">
  <img src="assets/project-kyh.gif" width="100%" style="border-radius: 10px;">
</div>

[![Live System](https://img.shields.io/badge/Live_System-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://kyh.bhuktatech.in/)
[![Code](https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github)](https://github.com/megabytis/project-kyh)

<br>

### 🛒 **ShopNexus — Production-Style E-Commerce Platform**
**Backend-Heavy Flagship E-Commerce Engine**

- Profiled live deployment thresholds under micro-burst concurrency using **k6**, executing **3,100+ requests** at a peak of **50 concurrent virtual users** to locate database bottlenecks and infrastructure compute constraints.
- Session-based authentication using JWT with refresh token rotation and HttpOnly cookies.
- Strict RBAC middleware protecting 25+ domain-modeled API routes (auth, products, cart, orders, admin).
- Redis caching layer for read-heavy query optimization and aggregation.
- Complete Stripe checkout, webhook confirmation, and refund processing lifecycle with idempotency handling.
- Deployed on **Vercel + Render + MongoDB Atlas**.

<div style="margin-bottom: 1rem;">
  <img src="assets/shopnexus.gif" width="100%" style="border-radius: 10px;">
</div>

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://shop-nexus-beta.vercel.app)
[![Code](https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github)](https://github.com/megabytis/shopnexus)

<br>

### 📄 **RAG-DocumentQnA — AI Document Search**
**Hybrid Search & Cross-Encoder Re-Ranking Engine**

- Built a dual-service architecture (Node.js API gateway + Python AI backend) supporting PDF, TXT, and DOCX document parsing with session isolation.
- Reduced LLM hallucinations by engineering a **Hybrid Search** engine combining dense vector embeddings (ChromaDB) with BM25 lexical keyword matching.
- Implemented a **Cross-Encoder re-ranker** pipeline to evaluate chunk relevancy score before context injection.

[![Code](https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github)](https://github.com/megabytis/RAG-DocumentQnA)

<br>

### 🎓 **LearnSphere — Full-Stack LMS with Payment Integration**

- JWT auth with refresh token flow + secure cookie handling.
- 3-tier RBAC — Student, Instructor, Admin with isolated route guards.
- Full course & lesson CRUD with free preview support.
- Stripe Checkout integration with webhook-based enrollment confirmation.
- Feature-based modular backend architecture (auth, course, lesson, payment).

<div style="margin-bottom: 1rem;">
  <img src="assets/learnsphere.gif" width="100%" style="border-radius: 10px;">
</div>

[![Live Demo](https://img.shields.io/badge/Live_Demo-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://learn-sphere-neon.vercel.app)
[![Code](https://img.shields.io/badge/Code-181717?style=for-the-badge&logo=github)](https://github.com/megabytis/LearnSphere)

<br>

## 🧠 What I Focus On
- Multi-Agent Graph Workflows (LangGraph, State Management)
- High-Concurrency Backend Architecture & API Contract Design
- Latency Profiling, Indexing, and Caching (k6, Redis, MongoDB)
- Containerized Cloud Deployments (Docker Compose, AWS EC2, Nginx, SSL)
- Hybrid Vector Search (BM25 + Dense Embeddings + Re-Ranking)

<br>

## 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=megabytis&show_icons=true&theme=tokyonight" width="48%">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=megabytis&theme=tokyonight" width="48%">
</div>

<br>

## 🌐 Connect With Me
<div align="center">
  <a href="mailto:madhusudanbhukta.dev@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/madhusudan-bhukta/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://madhusudan-portfolio-jade.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="https://x.com/rwar_star">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/>
  </a>
</div>

<br>

<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=megabytis&label=Profile%20views&color=7F3FBF&style=flat" />
</p>
