
# 📚 Smart Research Assistant using RAG + LLM (Groq + LangChain LCEL)

An AI-powered Smart Research Assistant that answers user queries from uploaded documents using Retrieval-Augmented Generation (RAG).
This project follows the latest LangChain modular architecture and integrates Groq-hosted LLaMA 3.1 models.

---

## 🚀 Features
- PDF document ingestion
- Semantic search using embeddings
- FAISS vector database
- Retrieval-Augmented Generation (RAG)
- Citation-based answers
- Groq LLaMA 3.1 integration
- LCEL-based pipeline
- Google Colab compatible

---

## 🧠 Architecture
User Query → Embeddings → FAISS → Retrieved Chunks → Groq LLaMA → Answer + Citations

---

## 🗂️ Project Structure
Smart_Research_Assistant_RAG/
├── notebooks/
├── data/
├── faiss_index/
├── src/
├── requirements.txt
└── README.md

---

## ▶️ Run Instructions
1. Open Google Colab
2. Upload the notebook
3. Run cells sequentially
4. Set GROQ_API_KEY
5. Upload PDFs
6. Ask questions

---

## 🔄 Major Updates
- Migrated to latest LangChain modular imports
- Added langchain-text-splitters and langchain-groq
- Switched LLM provider from Gemini to Groq
- Final model: llama-3.1-8b-instant
- Refactored RAG using LangChain Expression Language (LCEL)
- Updated chain invocation to `.invoke()`

---


---

## 📜 License
MIT
