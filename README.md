# Code Embedding Pipeline using CodeBERT

This project demonstrates how to generate semantic vector embeddings for Python code snippets using Hugging Face's `microsoft/codebert-base` model. The embeddings are stored in JSON format and FAISS index for similarity search.

## 🔧 Features
- Uses CodeBERT to extract embeddings from code
- Supports saving in JSON and FAISS
- Colab-compatible
- Simple and modular code

## 📂 Files
- `embed_code.ipynb` – Google Colab notebook
- `embeddings.json` – Code embeddings
- `faiss_index.index` – Vector search index
- `research.md` – Architecture and model background
- `code_snippets/` – Sample Python functions

## 📌 Requirements
- transformers
- torch
- faiss-cpu
- numpy

