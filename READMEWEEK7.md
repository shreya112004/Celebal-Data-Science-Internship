# Document Question Answering using RAG

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system that answers questions from PDF documents.

## Technologies Used
- Python
- LangChain
- Hugging Face Transformers
- Sentence Transformers
- FAISS
- PyPDF

## Workflow
1. Load PDF
2. Split text into chunks
3. Generate embeddings
4. Store embeddings in FAISS
5. Retrieve relevant chunks
6. Generate answers using FLAN-T5

## Sample Query
Question:
What is SQL Injection?

Answer:
Malicious SQL code is inserted into input fields to manipulate backend databases.
