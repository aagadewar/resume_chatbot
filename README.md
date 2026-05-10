# AI-Powered HR Resume Screening Chatbot

An intelligent HR assistant chatbot that analyzes candidate resumes against job descriptions and determines candidate-job fit using LLMs, vector embeddings, and semantic search.

Built using **LangChain**, **Groq Llama 3.3 70B**, **HuggingFace Embeddings**, **ChromaDB**, and **Streamlit**.

---

## 🚀 Features

- 📄 Upload and analyze candidate resumes
- 🧠 Extract skills, technologies, and experience from resumes
- 🎯 Match resumes against job descriptions
- ✅ Determine candidate-job fit
- 💬 Conversational chatbot interface for HR teams
- ⚡ Fast inference using Groq-hosted Llama models
- 🔍 Semantic search with vector embeddings
- 🌐 Deployed on Streamlit Cloud

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-------------|
| LLM Framework | LangChain |
| LLM Model | Groq - llama-3.3-70b-versatile |
| Embeddings | HuggingFaceEmbeddings |
| Vector Database | ChromaDB |
| Frontend/UI | Streamlit |
| Deployment | Streamlit Cloud |
| Language | Python |

---

## 📌 Architecture Overview

1. User uploads candidate resume
2. Resume text is extracted and chunked
3. Embeddings are generated using HuggingFace
4. Resume vectors stored in ChromaDB
5. HR enters Job Description
6. Relevant resume context retrieved using semantic search
7. Llama 3.3 70B model evaluates:
   - Skills match
   - Experience relevance
   - Technology alignment
   - Overall candidate fit
8. Chatbot provides HR-friendly response and recommendations

---
