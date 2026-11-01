<div align="center">

![Moheez Azam Kiani — AI/ML Developer & Backend Systems](assets/header.svg)

<br/>

[![Email](https://img.shields.io/badge/Email-moheezkiani01%40gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=white)](mailto:moheezkiani01@gmail.com)
[![Website](https://img.shields.io/badge/Website-aitoolspak.com-1e293b?style=flat-square&logo=googlechrome&logoColor=white)](https://aitoolspak.com/)
[![GitHub](https://img.shields.io/badge/GitHub-moheezkiani01-334155?style=flat-square&logo=github&logoColor=white)](https://github.com/moheezkiani01)
[![Location](https://img.shields.io/badge/Location-Lahore%2C%20Pakistan-0f172a?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

### Introduction

I am an **AI/ML Developer** and **Backend Engineer** studying Artificial Intelligence at **Superior University Lahore** (BS AI, expected 2028).

My work focuses on bridging machine-learning systems with reliable, production-oriented software architectures. Rather than isolated notebook experiments, I engineer end-to-end applications: pairing large language models, retrieval pipelines, and computer vision backbones with deterministic RESTful APIs, relational databases, and secure administrative controls.

---

### About Me

- **Education & Engineering Focus:** Undergraduate in Artificial Intelligence at Superior University Lahore (class of 2028), concentrating on machine learning, natural language processing, and scalable backend design.
- **Applied AI & Systems:** Experienced in architecting full-stack AI applications where probabilistic model outputs (LLMs, vision classifiers) are governed by strict backend validation, type safety, and database constraints.
- **Backend & Data Foundations:** Solid foundation in Python (FastAPI, Flask), relational schema modeling (PostgreSQL, MS SQL Server, SQLite), stored procedures, ORM design, and containerized deployment with Docker.
- **Engineering Philosophy:** Prioritizing grounded accuracy over unconstrained generation, observable architecture over black boxes, and clean, maintainable codebases over quick prototypes.

---

### Featured Engineering Projects

#### 1. AI Doctor
*Comprehensive Healthcare Management & Clinical Workflow Platform*

- **Problem & Solution:** Modern clinical workflows require rigid isolation between patient portals, doctor verification, hospital administration, and diagnostic data. AI Doctor provides an enterprise-grade backend coordinating role-based healthcare workflows with planned clinical AI assistance.
- **Engineering Highlights:**
  - Designed modular **FastAPI** backend with **PostgreSQL** relational persistence, managed via **SQLAlchemy** and **Alembic** database migrations.
  - Built comprehensive **Role-Based Access Control (RBAC)** and JWT authentication covering patient records, verified medical practitioners, and hospital administrative staff.
  - Implemented structured schemas for doctor credential verification, hospital affiliations, appointment slot reservation, and diagnostic record auditing.
  - Structured service boundaries to support future medical-evidence grounding and clinical assistant modules with strict safety boundaries.
- **Tech Stack:** `Python` · `FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `JWT` · `Docker`
- **Status:** *Active Private Development* (Protected repository; architecture and proprietary clinical workflows preserved).

---

#### 2. Hospital AI Assistant
*Multilingual Virtual Receptionist & Grounded Appointment System* · [Repository](https://github.com/moheezkiani01/Hospital-AI-Assistance)

- **Problem & Solution:** Healthcare front desks face severe queue congestion and multilingual communication barriers. Hospital AI Assistant handles natural patient inquiries, appointment scheduling, and clinic guidance in English, Urdu, and Roman Urdu.
- **Engineering Highlights:**
  - **Hybrid AI Architecture:** Routes conversational intent through LLMs while delegating schedule lookups, slot validation, booking, and cancellations to deterministic backend services.
  - **Evidence-Grounded RAG:** Ingests clinic policies and medical department documents, retrieving verified passages to answer patient questions and prevent medical hallucinations.
  - **Operational Reliability:** Features stateful conversational memory, duplicate-slot database uniqueness constraints, provider failover routing, rate limiting, and an administrative oversight dashboard.
- **Tech Stack:** `Python` · `FastAPI` · `SQLAlchemy` · `SQLite / PostgreSQL` · `Pydantic` · `Google Gemini API` · `RAG` · `Docker Compose`

---

#### 3. AI Tools PAK
*Full-Stack AI Discovery Directory & Cloud Architecture* · [Live Platform](https://aitoolspak.com/) · [Reference Repository](https://github.com/moheezkiani01/AI-Tools-PAK-Cloudflare)

- **Problem & Solution:** Navigating the ecosystem of artificial intelligence tools requires fast discovery, categorical filtering, and reliable product data. AI Tools PAK is a production platform cataloging AI software and services.
- **Engineering Highlights:**
  - **Edge Deployment & SEO:** Built with React and Vite, utilizing server-side pre-rendering for product collections and deep-link SEO optimization across search engines.
  - **Cloud Infrastructure & Data Security:** Powered by an Express serverless API running on Cloudflare Workers and Vercel, integrated with **Supabase PostgreSQL** protected by Row Level Security (RLS) policies and atomic database functions.
  - **Administrative Suite:** Implemented a secure administrative management dashboard for product indexing, metadata curation, and inventory status tracking.
- **Tech Stack:** `React` · `Vite` · `Node.js` · `Express` · `Cloudflare Workers` · `Supabase PostgreSQL` · `Vercel`
- *Note:* The public repository documents the Cloudflare Workers / Vercel serverless reference architecture; the live production catalogue is actively served at [aitoolspak.com](https://aitoolspak.com/).

---

#### 4. AI Resume Screening System
*NLP-Driven Candidate Evaluation & Skill Extraction Engine* · [Repository](https://github.com/moheezkiani01/AI_Resume_Screening_System_App) · [Live Demo](https://ai-resume-screening-system-app.vercel.app)

- **Problem & Solution:** High-volume recruitment causes hiring delays and inconsistent evaluations. This platform automates resume screening against job specifications using deep NLP analysis rather than naive keyword counts.
- **Engineering Highlights:**
  - **Four-Tier Scoring Engine:** Calculates composite candidate compatibility by blending **spaCy semantic vector similarity (40%)**, **TF-IDF relevance ranking (30%)**, direct keyword matching (20%), and named entity recognition (10%).
  - **Skill & Entity Detection:** Automatically extracts 60+ technical and soft skills, analyzes resume sentiment, identifies key experience phrases, and classifies candidates from *Outstanding* to *Not Suitable*.
  - **Audit & History:** Persists candidate dossiers, score breakdowns, and structured HR interview recommendations in SQLite for comparative recruiter reviews.
- **Tech Stack:** `Python` · `Flask` · `spaCy` · `scikit-learn` · `SQLite` · `HTML5 / CSS3` · `Vercel`

---

#### 5. Deepfake Detector
*Vision Classifier for Manipulated Media Detection* · [Repository](https://github.com/moheezkiani01/DeepFake_Detector)

- **Problem & Solution:** Proliferation of hyper-realistic synthetic media presents identity theft and disinformation challenges. Deepfake Detector classifies authentic versus manipulated facial media.
- **Engineering Highlights:**
  - **EfficientNet-B0 Backbone:** Fine-tuned convolutional architecture balancing lightweight parameter size with high classification sensitivity across facial artifact patterns.
  - **Modular PyTorch Lightning Pipeline:** Clean training harness featuring custom multi-source hybrid dataset loaders, learning rate schedulers, early stopping callbacks, and declarative hyperparameter configuration (`config.yaml`).
  - **Web Inference Interface:** Flask-based inference server offering drag-and-drop media upload, frame preprocessing, and real-time probability confidence scoring.
- **Tech Stack:** `Python` · `PyTorch` · `PyTorch Lightning` · `EfficientNet-B0` · `Torchvision` · `OpenCV` · `Flask`

---

#### 6. BookWise Recommender
*Hybrid Recommendation Engine with Offline Evaluation* · [Repository](https://github.com/moheezkiani01/BookWise_Recommender)

- **Problem & Solution:** Standalone collaborative filtering suffers from cold-start items, while pure content filtering limits serendipitous discovery. BookWise fuses both methodologies into a balanced hybrid recommender.
- **Engineering Highlights:**
  - **Ensemble Hybrid Scoring:** Blends Singular Value Decomposition (**SVD matrix factorization**) for collaborative user-rating patterns with **TF-IDF cosine similarity** for book genres and descriptions.
  - **Quantitative Offline Evaluation:** Features automated benchmark scripts calculating Precision@K, Recall@K, and NDCG@K across interaction datasets.
  - **RESTful API:** Deployed as a high-performance **FastAPI** service with Pydantic request/response validation, interactive OpenAPI documentation, and configurable weights.
- **Tech Stack:** `Python` · `FastAPI` · `scikit-learn` · `Surprise / SVD` · `TF-IDF` · `Pydantic` · `Uvicorn`

---

#### 7. VaultManager Pro
*Enterprise Core Banking Management & Transaction Engine* · [Repository](https://github.com/moheezkiani01/Vault_Manager_Pro)

- **Problem & Solution:** Financial institutions demand zero-tolerance transaction integrity, auditable role segregation, and automated risk enforcement. VaultManager Pro is a relational banking system.
- **Engineering Highlights:**
  - **Relational Integrity & Stored Procedures:** Built on **Microsoft SQL Server**, executing customer onboarding, multi-account ledger transfers, and interest calculations via pre-compiled T-SQL stored procedures.
  - **Automated Credit Risk Assessment:** Algorithmic loan evaluation procedure that automatically approves, prices (4.5% to 8.5% interest), or rejects applications based on active balance liquidity ratios.
  - **Trigger-Based Fraud Detection:** T-SQL database triggers monitoring real-time withdrawal anomalies (unusual amounts, rapid balance depletion) and automating end-of-month repayment deductions.
- **Tech Stack:** `Python` · `Flask` · `Microsoft SQL Server` · `T-SQL` · `pyodbc` · `HTML / CSS`

---

### Technical Expertise

| Domain | Technologies & Frameworks |
|---|---|
| **AI & Machine Learning** | PyTorch, PyTorch Lightning, scikit-learn, EfficientNet-B0, OpenCV, NumPy, Pandas, Model Evaluation |
| **NLP, LLMs & RAG** | Retrieval-Augmented Generation (RAG), Vector Embeddings, LangChain, FAISS, Chroma, spaCy, TF-IDF |
| **Backend & API Engineering** | Python, FastAPI, Flask, RESTful APIs, Pydantic, SQLAlchemy, Alembic, JWT, Role-Based Access Control |
| **Databases & Systems** | PostgreSQL, Supabase, Microsoft SQL Server, SQLite, T-SQL (Stored Procedures, Triggers, Views), RLS |
| **Frontend & Cloud Deployment** | React, JavaScript, Vite, Node.js, Express, Docker, Docker Compose, Cloudflare Workers, Vercel |
| **Engineering Tooling** | Git, GitHub, Linux / PowerShell, Uvicorn, Postman, py.test |

---

### Engineering Journey

- **Foundations in Computing & Numerical Analysis**  
  Algorithmic problem-solving, object-oriented design, data structures, and numerical data manipulation using Python, NumPy, and Pandas.

- **Machine Learning & Computer Vision**  
  Supervised and unsupervised learning, convolutional neural networks, transfer learning, and synthetic media classification with PyTorch and EfficientNet-B0.

- **NLP, Information Retrieval & Recommendation Systems**  
  Vector space modeling, semantic vector similarity with spaCy, SVD collaborative filtering, and Retrieval-Augmented Generation (RAG) with vector search.

- **Production Backend Architecture & Database Systems**  
  Designing robust, type-safe REST APIs with FastAPI and Flask; architecting relational database schemas, stored procedures, triggers, and RBAC with PostgreSQL and MS SQL Server.

- **Full-Stack AI Applications & Cloud Infrastructure**  
  Building and shipping complete applications connecting probabilistic AI pipelines with deterministic business logic; deploying to Cloudflare Workers, Vercel, and Docker.

---

### Currently Building & Exploring

- **Clinical Healthcare AI:** Architecting fault-tolerant, verifiable assistant pipelines with explicit safety boundaries and zero tolerance for clinical hallucinations.
- **RAG Evaluation Frameworks:** Benchmarking context retrieval precision, passage reranking, and generation faithfulness in domain-specific retrieval systems.
- **High-Throughput Asynchronous APIs:** Deepening patterns in asynchronous Python, connection pooling, and distributed background task processing with FastAPI and PostgreSQL.

---

### Contact & Profiles

- **Email:** [moheezkiani01@gmail.com](mailto:moheezkiani01@gmail.com)
- **GitHub:** [github.com/moheezkiani01](https://github.com/moheezkiani01)
- **Live Platform:** [aitoolspak.com](https://aitoolspak.com/)
- **Location:** Lahore, Pakistan
