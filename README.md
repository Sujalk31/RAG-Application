# 📄 Chat with Your Documents — RAG App (Chroma + Groq + Streamlit)

A Retrieval-Augmented Generation (RAG) web application that allows users to upload documents and interact with them using natural language queries powered by an LLM.

Built with Streamlit, LangChain, ChromaDB, HuggingFace embeddings, and Groq’s OpenAI-compatible API.

---

## 🚀 Features

- Upload multiple documents at once  
- Supports PDF, TXT, and DOCX formats  
- Automatic document parsing  
- Intelligent text chunking  
- Embedding generation using MiniLM  
- Persistent vector database (ChromaDB)  
- Semantic similarity search  
- Context-aware LLM responses  
- Interactive chat interface with history  
- Local storage (no cloud database required)  
- Reuse processed documents without re-embedding  

---

## 🧠 How It Works (RAG Pipeline)

1. User uploads documents  
2. Documents are parsed into raw text  
3. Text is split into manageable chunks  
4. Each chunk is converted into embeddings  
5. Embeddings are stored in Chroma vector database  
6. User asks a question  
7. Relevant chunks are retrieved via similarity search  
8. LLM generates an answer using retrieved context  

---

## 🏗️ Tech Stack

**Frontend:** Streamlit  
**RAG Framework:** LangChain  
**Vector Database:** ChromaDB  
**Embeddings:** HuggingFace — `all-MiniLM-L6-v2`  
**LLM:** Groq API — LLaMA-3.1-8B-Instant  
**Document Loaders:** PyPDF, TextLoader, Docx2txt  

---

## 📂 Supported File Types

- PDF (`.pdf`)  
- Text files (`.txt`)  
- Word documents (`.docx`)  


