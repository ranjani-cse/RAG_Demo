# RAG_Demo
# RAG Demo — Simple Retrieval-Augmented Generation

## What This Does
A simple RAG system that:
1. Converts text documents to vectors using Sentence-Transformers
2. Stores them in a FAISS index
3. Answers questions by retrieving the most relevant documents
4. Rejects unrelated questions with "I don't know"

## How to Run

### In Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ranjani-cse/RAG_Demo/blob/main/RAG_Examples.ipynb)

1. Open the notebook
2. Run the first cell to install dependencies
3. Run all cells

### Locally
```bash
pip install -r requirements.txt
python rag_demo.py
