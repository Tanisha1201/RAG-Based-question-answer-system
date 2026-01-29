# RAG-Based-question-answer-system
RAG-based Question Answering system using FastAPI, FAISS and HuggingFace.
This project implements a Retrieval-Augmented Generation (RAG) based Question Answering system using Python.  
It allows users to upload multiple text and PDF documents and ask questions whose answers are generated strictly from the uploaded documents.

---

## 🚀 Features
- Supports both TXT and PDF files  
- Handles multiple documents at the same time  
- Uses Sentence Transformers for embeddings  
- Uses FAISS for fast vector search  
- Uses a language model (FLAN-T5) for answer generation  
- Returns source file names for transparency  
- Supports single and multiple questions  

---

## 🛠️ Technologies Used
- Python  
- Sentence-Transformers  
- FAISS  
- PyPDF2  
- Transformers  
- FastAPI  
- Torch
