# FastAPI Documentation RAG

This project demonstrates a Retrieval-Augmented Generation (RAG) system
built using LangChain and FastAPI's official documentation.

## Features
- Loads FastAPI documentation using WebBaseLoader
- Chunks and embeds documentation text
- Retrieves relevant sections for user queries
- Generates grounded answers using an LLM

## Tech Stack
- Python
- LangChain
- FAISS
- Google AI Studio (Gemini)
- OpenAI / HuggingFace embeddings

## Use Case
Designed to reduce hallucinations when answering FastAPI-related developer questions.

## Future Improvements
- Code-aware chunking
- Source citations per answer
- UI for interactive querying
