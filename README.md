# RAG Chatbot

A Retrieval-Augmented Generation chatbot that answers user questions from uploaded documents using embeddings, vector search, and an LLM.

## Features
- Upload and process documents
- Split text into chunks
- Generate embeddings
- Store embeddings in a vector database
- Retrieve relevant context for user queries
- Generate context-aware answers

## Tech Stack
- Python
- Streamlit
- LangChain
- FAISS
- OpenAI / HuggingFace embeddings

## Project Workflow
1. Upload document
2. Extract text
3. Split text into chunks
4. Create embeddings
5. Store embeddings in FAISS
6. Retrieve relevant chunks
7. Generate final answer using LLM

## Folder Structure
```bash
src/
app.py
requirements.txt
README.md
