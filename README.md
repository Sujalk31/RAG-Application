#📄 Chat with Your Documents — RAG App (Chroma + Groq + Streamlit)

A Retrieval-Augmented Generation (RAG) web application that allows users to upload documents and chat with them using an LLM.

Built with Streamlit, LangChain, ChromaDB, HuggingFace embeddings, and Groq LLM API.

🚀 Features

✅ Upload multiple documents
✅ Supports PDF, TXT, DOCX
✅ Automatic text chunking
✅ Embedding generation (MiniLM)
✅ Persistent vector database (ChromaDB)
✅ Semantic search retrieval
✅ LLM-powered answers grounded in documents
✅ Chat interface with history
✅ Local storage (no cloud DB required)

🧠 How It Works (RAG Pipeline)
User uploads documents
Documents are parsed into text
Text is split into chunks
Each chunk → converted to embeddings
Embeddings stored in Chroma vector database
User asks a question
Relevant chunks retrieved via similarity search
LLM generates answer using retrieved context
🏗️ Tech Stack
Frontend: Streamlit
RAG Framework: LangChain
Vector Database: ChromaDB
Embeddings: HuggingFace (all-MiniLM-L6-v2)
LLM: Groq API (LLaMA-3.1-8B-Instant)
Document Loaders: PyPDF, TXT, DOCX
📂 Supported File Types
PDF (.pdf)
Text files (.txt)
Word documents (.docx)
