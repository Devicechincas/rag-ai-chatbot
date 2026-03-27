# RAG-Based AI Chatbot

This project implements a Retrieval-Augmented Generation (RAG) based chatbot using LangChain and OpenAI.

## Features
- Document-based question answering
- Vector database using FAISS
- LLM-powered response generation
- Scalable AI pipeline

## Tech Stack
- Python
- LangChain
- OpenAI API
- FAISS (Vector Database)

## How it Works
1. Load documents
2. Convert text into embeddings
3. Store embeddings in vector database
4. Retrieve relevant context
5. Generate response using LLM

## Run the Project
pip install -r requirements.txt  
python app.py

## Future Improvements
- Add Streamlit UI
- Support PDF documents
- Improve retrieval accuracy
