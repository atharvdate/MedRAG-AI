# MedRAG-AI : A Retrieval-Augmented Medical Chatbot using LLMs, LangChain, Pinecone - Vector database &amp; AWS

MedRAG-AI is a project I am currently building to explore how Retrieval-Augmented Generation (RAG) can be applied in the medical domain. The goal is to create a system that can answer medical queries using context from documents instead of relying only on a language model.

## Status

This project is under active development. The base structure and backend setup are in place, and I am currently working on integrating the core RAG pipeline.

## Current Setup

- Flask-based backend initialized  
- Modular project structure using `src/`  
- Helper functions and prompt templates created  
- Research and experimentation done in notebooks  
- Project packaging configured using `setup.py`  

## Project Structure

- `app.py` → entry point for Flask application  
- `src/` → core logic (helpers, prompts, etc.)  
- `research/` → experimentation and testing  
- `requirements.txt` → dependencies  
- `setup.py` → package configuration  

## What I am working on

- Implementing document ingestion and preprocessing  
- Generating embeddings using transformer models  
- Integrating Pinecone for vector storage  
- Building retrieval and response pipeline  
- Connecting everything to the Flask API  

## Tech Stack

- Python  
- Flask  
- LangChain  
- OpenAI API  
- Pinecone  
- Sentence Transformers
- AWS

## How to run

Clone the repository : git clone https://github.com/atharvdate/MedRAG-AI.git

Navigate to the project folder : cd MedRAG-AI

Create environment : conda create -n medrag python=3.10 -y

Activate environment : conda activate medrag

Install dependencies : pip install -r requirements.txt

Run the application : python app.py

## Note

This is an ongoing project. The core RAG functionality is still being implemented and the structure may evolve as development progresses.

## Developer

Atharv Avirat Date  
LinkedIn: https://www.linkedin.com/in/atharv-date-a763b724a  
Email: atharvdate5114@gmail.com
