# fastapi-chromadb-rag
# FastAPI ChromaDB RAG

This project implements a lightweight FastAPI server for Retrieval-Augmented Generation (RAG). It uses ChromaDB for persistent document storage and querying, and the `sentence-transformers/all-MiniLM-L6-v2` model from Hugging Face for generating embeddings.

## Features

- **Document Ingestion**: Upload documents in PDF, DOCX, or TXT format. The server will parse the text and store the embeddings in ChromaDB.
- **Querying**: Query the documents using natural language text, and retrieve the most relevant documents based on embeddings.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/fastapi-chromadb-rag.git
   cd fastapi-chromadb-rag
