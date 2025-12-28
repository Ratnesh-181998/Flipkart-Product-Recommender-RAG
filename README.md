# 🛒 GenAI RAG Product Recommender

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://universal-pdf-rag-chatbot-mhsi4ygebe6hmq3ij6d665.streamlit.app/)
[![Python 3.9+](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=flat&logo=kubernetes&logoColor=white)](https://kubernetes.io/)

> **A production-grade E-commerce Recommendation System built with RAG Architecture, Groq Llama 3, LangChain, and AstraDB.** 
> *Deployed on Kubernetes with Prometheus/Grafana O11y.*

---

## ⚡ Overview

The **Flipkart Product Recommender** is an intelligent conversational AI that goes beyond keyword search. It leverages **Retrieval-Augmented Generation (RAG)** to understand user intent and semantically retrieve relevant product reviews from **AstraDB**, generating helpful responses using **Groq's Llama 3.1** engine.

This project demonstrates a complete **End-to-End LLMOps Pipeline**, including data ingestion, vector storage, RAG chain orchestration, backend API, frontend UI, and cloud-native deployment.

---

## 🚀 Live Demo

- **🌐 Streamlit App:** [Click Here to Try](https://universal-pdf-rag-chatbot-mhsi4ygebe6hmq3ij6d665.streamlit.app/)
- **🐙 GitHub Repository:** [Ratnesh-181998/Flipkart-Product-Recommender-RAG](https://github.com/Ratnesh-181998/Flipkart-Product-Recommender-RAG)

---

## 🏗️ Architecture & Tech Stack

The system follows a modern **Microservices Architecture**:

### 🧠 Core AI Stack
- **LLM:** Groq (Llama 3.1-8B-Instant) - *Ultra-low latency inference*
- **Embeddings:** HuggingFace (`BAAI/bge-base-en-v1.5`)
- **Vector Store:** Datastax AstraDB (Serverless Cassandra)
- **Orchestration:** LangChain

### 💻 Application Layer
- **Frontend:** Streamlit (Python) / HTML / CSS
- **Backend:** Flask (Python REST API)
- **Monitoring:** Prometheus (Metrics) & Grafana (Dashboards)

### 🐳 DevOps & Deployment
- **Containerization:** Docker
- **Orchestration:** Kubernetes (Minikube on GCP VM)
- **CI/CD:** GitHub Actions (Planned)

---

## 📱 UI Features (Application Tabs)

### 1️⃣ 🎬 **Live Demo**
The main interface where users interact with the Recommendation Engine.
- **Chat Interface:** ChatGPT-style conversational UI.
- **Product Cards:** AI dynamically generates product cards with Price, Rating, and "Buy Now" links.
- **Real-time RAG:** Fetches context from thousands of reviews in milliseconds.

### 2️⃣ 📖 **About Project**
A detailed breakdown of the problem statement and solution.
- **Problem:** Keyword search fails to understand context (e.g., "good camera phone for night shots").
- **Solution:** Semantic Vector Search bridges the gap between query and data.
- **Impact:** Increases conversion rates and user engagement.

### 3️⃣ 🔧 **Tech Stack**
Visual representation of the technologies used.
- **Frontend:** HTML/CSS, Streamlit
- **Backend:** Flask, LangChain
- **Database:** AstraDB (Vector)
- **AI:** Groq, HuggingFace
- **Monitoring:** Prometheus, Grafana

### 4️⃣ 🏗️ **Architecture**
Interactive diagrams explaining the system flow.
- **Data Flow:** Ingestion -> Embedding -> Storage -> Retrieval.
- **Workflow:** User -> UI -> API -> RAG Chain -> LLM.
- **Deep Dive:** Detailed explanation of the Kubernetes deployment.

### 5️⃣ 📋 **System Logs**
Real-time dashboard for developers.
- **Live Logs:** Tracks INFO, WARNING, and ERROR events.
- **Health Checks:** Monitors status of Flask, Database, and LLM connections.
- **Metrics:** Counts total API calls and errors.

---

## 🛠️ Local Installation

### Prerequisites
- Python 3.9+
- Docker (optional)
- Git

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ratnesh-181998/Flipkart-Product-Recommender-RAG.git
   cd Flipkart-Product-Recommender-RAG
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Environment Variables**
   Create a `.env` file in the root directory:
   ```env
   GROQ_API_KEY=your_groq_key
   ASTRA_DB_TOKEN=your_astra_token
   ASTRA_DB_API_ENDPOINT=your_endpoint
   ```

5. **Run the Application**
   ```bash
   streamlit run streamlit_app.py
   ```

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 📞 Contact

**RATNESH KUMAR SINGH**  
*Data Scientist (AI/ML) | 4+ Years Experience*

- 📧 **Email:** [rattudacsit2021gate@gmail.com](mailto:rattudacsit2021gate@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/ratneshkumar1998](https://www.linkedin.com/in/ratneshkumar1998/)
- 🐙 **GitHub:** [github.com/Ratnesh-181998](https://github.com/Ratnesh-181998)
- 📱 **Phone:** +91-947XXXXX46

---
*Built with ❤️ using LangChain, Groq, and Streamlit.*
