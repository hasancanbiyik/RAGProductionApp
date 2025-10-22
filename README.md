# 🧠 RAGProductionApp

**Production-Ready Retrieval-Augmented Generation (RAG) AI Agent**  
Built with **FastAPI**, **Inngest**, **OpenAI**, and **Qdrant**, this project demonstrates how to design an event-driven, production-oriented RAG pipeline in Python.

---

## 🚀 Overview

This app performs automated **document ingestion**, **chunking**, **embedding**, and **vector storage** using modern cloud-ready tools.  
It supports asynchronous workflow orchestration via **Inngest**, making it scalable and resilient for real-world AI applications.

### Key Features
- ⚡ **FastAPI** backend serving RAG endpoints  
- 🧩 **Inngest** event functions for asynchronous processing  
- 📄 **PDF loader & chunker** to preprocess large documents  
- 🔍 **Qdrant** vector database for semantic search and retrieval  
- 🤖 **OpenAI embeddings** for high-quality vector representations  
- 🌱 **Modular design** ready for extension (e.g., query answering, summarization)

---

## 🧰 Tech Stack

| Component | Purpose |
|------------|----------|
| **Python 3.11+** | Core language |
| **FastAPI** | API framework |
| **Inngest** | Function orchestration and event handling |
| **Qdrant** | Vector database for embeddings |
| **OpenAI API** | Embedding model (`text-embedding-3-small`) |
| **PyPDF** | PDF parsing |
| **dotenv** | Environment variable management |
| **uvicorn** | ASGI server |
## 🗂️ Project Structure

