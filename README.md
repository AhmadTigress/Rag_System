# Rag_System
Medical knowledge assistant designed specifically for use in Obstetrics and Gynaecology (O&G). 

# O&G RAG Assistant

**Retrieval-Augmented Generation (RAG) System for Obstetrics & Gynaecology**

This is an AI-powered knowledge retrieval tool designed to support **medical students, resident doctors, and consultants** with fast, accurate answers in **Obstetrics and Gynaecology**. 
The system combines **retrieval-based search** and **generative AI** to deliver contextual, real-time insights from clinical literature, guidelines, and EMRs.

---

##  Features

-  **Context-aware Q&A** using LLMs and a vector store backend
-  **Custom knowledge ingestion** from O&G textbooks, lecture notes, and clinical protocols
-  **Hugging Face Embeddings** for semantic similarity search
-  **ChromaDB** as the vector database for fast retrieval
- Supports evidence-based decision-making in clinical settings

---

## Tools & Libraries Used

- **Python 3.11+**
- **LangChain**
- **ChromaDB**
- **Hugging Face Transformers & Embeddings**
- **PyPDF**
- **Hugging Face (FLAN-T5)**

---

## Installation

```bash
git clone https://github.com/AhmadTigress/Rag_System.git
cd Rag_System
pip install -r requirements.txt
