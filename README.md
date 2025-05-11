# RAG Document Q&A

## Overview

RAG Document Q&A is a Streamlit application that leverages the power of retrieval-augmented generation (RAG) to provide an interactive question-and-answer interface for research papers. This application uses the Groq API and the Llama3 model along with the Hugging Face embedding model to generate accurate responses based on the context provided by the documents.

## Features

- **Document Upload**: Load research papers from a specified directory.
- **Text Splitting**: Automatically splits documents into manageable chunks for better processing.
- **Vector Embeddings**: Converts document chunks into vector embeddings using Hugging Face's sentence-transformers model and stores them in a FAISS vector database.
- **Interactive Q&A**: Users can input questions and receive context-based answers from the loaded documents.
- **Document Similarity Search**: Explore similar documents based on the user's query.
