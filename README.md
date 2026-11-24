<h1 align="center">Mohamed Gaber</h1>

<p align="center">
  <b>AI Engineer</b> · Generative AI · Agentic AI · RAG · Multi-Agent Systems<br/>
  Cairo, Egypt
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mogaber2004"><img src="https://img.shields.io/badge/LinkedIn-mogaber2004-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mohamedgaberr63@gmail.com"><img src="https://img.shields.io/badge/Email-mohamedgaberr63@gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.kaggle.com/mhmedgaber"><img src="https://img.shields.io/badge/Kaggle-mhmedgaber-20BEFF?style=flat&logo=kaggle&logoColor=white" alt="Kaggle"/></a>
</p>

---

## About

I am an AI Engineer who designs and builds production-oriented applications powered by Large Language Models (LLMs). My work centers on **multi-agent systems, Retrieval-Augmented Generation (RAG), GraphRAG, and NLP pipelines**, built on modern AI frameworks and scalable backend architectures.

I focus on turning complex, real-world problems into reliable intelligent applications across the **legal, banking, healthcare, and knowledge-intensive** domains.

> **Open to AI Engineer opportunities, collaborations, and challenging AI projects.**

---

## Core Expertise

| Area | Focus |
|---|---|
| **Generative AI & LLMs** | LLM applications, prompt engineering, fine-tuning |
| **Agentic AI** | Multi-agent systems, LangGraph, LangChain, MCP |
| **Retrieval Systems** | RAG, GraphRAG, semantic search, embeddings |
| **Machine Learning** | NLP, deep learning, Transformers, PyTorch |
| **Applied AI** | Legal intelligence, banking automation, clinical Q&A |
| **Backend Engineering** | FastAPI, REST APIs, microservices |

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java_(Basic)-ED8B00?style=flat&logo=openjdk&logoColor=white)

**AI / Machine Learning**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat)

**RAG & Knowledge Systems**
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat)

**Backend & Databases**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

**Data & Infrastructure**
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Featured Projects

### ⚖️ El Mostashar: Egyptian Criminal Legal Case Solver
*Multi-agent system · Feb – Jun 2026*

An end-to-end system that analyzes Egyptian criminal cases, from raw document ingestion to a structured Arabic judgment.

- Architected a **10-agent framework** in LangGraph covering procedural auditing, multi-layer evidence evaluation, and structured Arabic judgment generation.
- Built a **Neo4j knowledge graph** as the legal memory layer, linking Penal Code articles, Court of Cassation precedents, charges, and case entities for **multi-hop GraphRAG** retrieval.
- Added **FAISS dense retrieval** over an Arabic legal corpus (police minutes, lab reports, defense memos) to supply context to the analytical agents.
- Reduced latency with a **conditional early-exit flow** for procedural nullities and **concurrent node execution** in LangGraph, which helps most on multi-defendant cases.

`Python` `LangGraph` `LangChain` `GraphRAG` `Neo4j` `FAISS` `OpenAI`

### ✈️ Agentic AI Trip Planner
*Multi-tool ReAct agent · Jan 2026*

- Built an autonomous **ReAct agent** in LangGraph that orchestrates **4+ external APIs** (weather, place search, currency conversion, cost calculation) to answer multi-step travel queries.
- Refactored a single-script prototype into a modular **FastAPI + Streamlit** application with consistent logging and exception handling.

`Python` `LangGraph` `FastAPI` `Streamlit`

### 🗄️ LLM-Powered SQL Database Agent
*Text-to-SQL agent · Jan 2026*

- Built a **LangGraph + Groq** workflow that translates natural-language questions into executable SQL and runs them through SQLAlchemy, with results shown in a Streamlit interface.
- Designed a decoupled **FastAPI** backend with dedicated `/generate-sql` and `/execute-sql` endpoints, separating the API from the frontend.
- Supports **MySQL and PostgreSQL**.

`Python` `LangGraph` `LangChain` `Groq` `FastAPI` `Streamlit` `SQLAlchemy` `PostgreSQL` `MySQL`

### 🏥 [Medical Chatbot: RAG-Based Clinical Q&A](https://github.com/mohamedGaber2004/Medical-ChatBot-APP)
*Nov 2025*

A conversational assistant that answers medical questions using context retrieved from a medical knowledge base stored in Pinecone.

`Python` `Flask` `LangChain` `OpenAI` `Pinecone` `Sentence Transformers`

### 🧠 Emotion Classification with DistilBERT
*Oct 2025*

- Ran exploratory data analysis on **16,000 training samples** (class distribution, text-length patterns).
- Fine-tuned `distilbert-base-uncased` with the Hugging Face Trainer API on **6 emotion categories**.
- Reached **93.0% test accuracy** and a **0.928 weighted F1-score**.

`Python` `PyTorch` `Transformers` `Scikit-learn` `Pandas` `NumPy`

### More Work

- [**EGBank OCR App**](https://github.com/mohamedGaber2004/EGBankInternshipProject_OCR_App): OCR application from my banking internship
- [**BERT Fine-Tuning for NER (CoNLL-2003)**](https://github.com/mohamedGaber2004/HuggingFace_BertFintune_Conll2003_NER): Hugging Face token classification
- [**Diabetes Detection**](https://github.com/mohamedGaber2004/ML_DiabetesDetection): classical ML classification
- [**Loan Approval Classification**](https://github.com/mohamedGaber2004/ML_LoanApprovalClassification): classical ML classification
- [**Vegetable Image Recognition**](https://github.com/mohamedGaber2004/DL_VegetableImageRecognition): deep learning image classification

---

## Experience

**AI Developer Intern · EGBank** · New Cairo, Egypt *(Jul 2025)*

- Built an automated **EasyOCR** pipeline and integrated it into an end-to-end document-processing workflow for extracting fields from diverse banking forms.
- Reduced manual data-entry time by approximately **40%**.
- Independently designed, built, and deployed a working proof of concept within a single agile sprint.

**Machine Learning Engineer Intern · Genius Technology Center (GTC)** · Remote *(Aug – Sep 2025)*

- Built an NLP preprocessing pipeline in Python that cleaned and standardized **45,000 news articles** using custom tokenization, lemmatization, and noise filtering.
- Improved dataset reliability by resolving missing entries and removing duplicate records.
- Sped up text normalization with optimized Pandas operations and contributed to architecture discussions on modular, reproducible code.

---

## Education

**B.Sc. in Computer Science** · Sadat Academy for Management Sciences, Maadi, Egypt *(Oct 2022 – Jun 2026)*

---

## Certifications

- **NVIDIA:** Building LLM Applications with Prompt Engineering
- **IBM:** Generative AI Engineering with LLMs (7-course specialization), including Fine-Tuning Transformers
- **DataCamp:** Retrieval-Augmented Generation (RAG) with LangChain
- **Udemy:** Agentic AI Bootcamp (LangGraph & LangChain)
- **DeepLearning.AI:** Natural Language Processing in TensorFlow
- **Stanford University:** Machine Learning, and Supervised Machine Learning: Regression and Classification
- **University of Glasgow:** Generative Pre-trained Transformers (GPT)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mohamedGaber2004&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true" width="49%" alt="GitHub stats (all-time commits and PRs)" />
  <img src="profile-summary-card-output/tokyonight/2-most-commit-language.svg" width="49%" alt="Most used languages" />
</p>

<p align="center">
  <img src="profile-summary-card-output/tokyonight/1-repos-per-language.svg" width="49%" alt="Repos per language" />
  <img src="profile-summary-card-output/tokyonight/4-productive-time.svg" width="49%" alt="Productive time" />
</p>

---

## Let's Connect

- **Email:** [mohamedgaberr63@gmail.com](mailto:mohamedgaberr63@gmail.com)
- **LinkedIn:** [linkedin.com/in/mogaber2004](https://www.linkedin.com/in/mogaber2004)
- **Kaggle:** [kaggle.com/mhmedgaber](https://www.kaggle.com/mhmedgaber)
- **GitHub:** [github.com/mohamedGaber2004](https://github.com/mohamedGaber2004)
