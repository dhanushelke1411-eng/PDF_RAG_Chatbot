# PDF RAG Chatbot

## Overview

This project is a Retrieval-Augmented Generation (RAG) chatbot that allows users to interact with PDF documents through natural language questions.

The system extracts text from PDFs, creates vector embeddings, stores them in a FAISS vector database, and uses Google Gemini to generate accurate context-aware answers.

---

## Problem Statement

Large PDF documents can be difficult to navigate and search manually. This project enables users to ask questions directly and receive relevant answers from the document content.

---

## Features

- PDF document ingestion
- Automatic text extraction
- Semantic search using vector embeddings
- Context-aware question answering
- FAISS vector database
- Gemini-powered responses

---

## Technologies Used

- Python
- LangChain
- Google Gemini API
- FAISS
- PyPDF
- Sentence Transformers
- Hugging Face Embeddings

---

## Architecture

PDF → Text Extraction → Text Chunking → Embeddings → FAISS Vector Store → Similarity Search → Gemini LLM → Answer Generation

---

## Project Workflow

1. Load PDF documents
2. Extract text content
3. Split text into chunks
4. Generate embeddings
5. Store embeddings in FAISS
6. Retrieve relevant chunks
7. Send context to Gemini
8. Generate final answer

---

## Dataset

- User-provided PDF documents
- Supports knowledge retrieval from custom PDFs

---

## Key Components

### Document Loader
- PyPDFLoader

### Text Splitter
- RecursiveCharacterTextSplitter

### Vector Database
- FAISS

### Embedding Model
- HuggingFace Embeddings

### LLM
- Google Gemini

---

## Example Use Cases

- Research paper Q&A
- Study material assistant
- Technical document chatbot
- Company policy assistant
- Book question-answering system

---

## Project Structure

PDF-RAG-Chatbot/
│
├── PDF_RAG_Chatbot.ipynb
├── README.md
└── requirements.txt

---

## Installation

```bash
pip install langchain
pip install langchain-community
pip install langchain-google-genai
pip install google-generativeai
pip install faiss-cpu
pip install pypdf
pip install sentence-transformers
```

## How to Run

1. Upload PDF document.
2. Configure Gemini API key.
3. Run all notebook cells.
4. Ask questions about the PDF.
5. Receive context-aware answers.

---

## Skills Demonstrated

- Retrieval-Augmented Generation (RAG)
- Large Language Models (LLMs)
- Vector Databases
- Semantic Search
- Prompt Engineering
- LangChain Framework
- Google Gemini Integration

---

## Future Improvements

- Multi-PDF support
- Streamlit web interface
- Chat history memory
- Hybrid search
- Advanced reranking

---

