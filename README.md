# RAG Chatbot

A modular Retrieval-Augmented Generation project that indexes PDF documents and retrieves relevant context for user queries.

## Features
- Upload PDF documents
- Extract text using PyPDFLoader
- Split content into semantic chunks
- Generate embeddings with Hugging Face
- Store vectors in FAISS
- Retrieve top relevant chunks for a question

## Tech Stack
- Python
- Streamlit
- LangChain
- Hugging Face Embeddings
- FAISS

## Project Structure
```text
app.py
src/
  loader.py
  splitter.py
  embeddings.py
  vectorstore.py
  retriever.py
