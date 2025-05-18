# PolicyRAG | Retrieval-Augmented Generation using HDFC Policy Documents

This project demonstrates the implementation of a Retrieval-Augmented Generation (RAG) system using HDFC health insurance policy PDFs. The aim is to build a scalable, robust LLM-powered solution featuring caching, semantic search, and reranking using the LLaMA model.

## 📁 Project Overview

The RAG system enables users to query large policy documents and receive accurate, context-aware answers. It supports:

- 📄 Text and table extraction from PDFs
- 🧠 Semantic search and reranking
- ⚡ Fast querying with cache support
- 🦙 LLaMA-based answer generation

### ✅ Key Steps Covered

- 📥 Loading and parsing HDFC policy PDFs
- 🧹 Preprocessing text, distinguishing between tables and regular content
- 📊 Efficient chunking and embedding storage
- 🔍 Similarity search and reranking
- 🤖 LLM-based response generation using LLaMA

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Place HDFC policy PDFs in the specified directory.
3. Run the notebook sequentially to process data and query the RAG pipeline.

## 📂 Project Structure

Policy_RAG.ipynb # Main Jupyter notebook
data/policies/*.pdf # Input HDFC documents

## ✍️ Author

Developed by Tejasvi Chandola<br>
Linkedin : https://www.linkedin.com/in/tejasvichandola/
