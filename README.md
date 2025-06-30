***🔍 First Steps with Croma: Retrieval-Augmented Generation & Re-ranking***

This repository contains my first experiments using Croma, a Python library for building Retrieval-Augmented Generation (RAG) pipelines. It includes basic implementations of:

Document retrieval using vector stores

Query expansion techniques

Cross-encoder re-ranking for improved retrieval accuracy

***Source Document Used:***

All retrieval pipelines were tested using the following research paper as the primary source document:

### Cultural Palette: Pluralising Culture Alignment via Multi-agent Palette
#### Jiahao Yuan, Zixiang Di, Shangzixin Zhao, Usman Naseem
### link: arXiv:2412.11167


***📁 Notebooks Overview*** 
1. RAG1.ipynb
A simple end-to-end RAG pipeline using Croma. This notebook:

Creates a vector store

Stores sample documents

Retrieves relevant chunks based on a query

2. QUERYEXPANSION.ipynb
Explores techniques to improve retrieval by expanding user queries. Includes:

Basic keyword-based expansion

Integration with Croma’s retriever to evaluate the effects

3. Cross-encoder Re-ranking.ipynb
Implements a cross-encoder model (e.g., from HuggingFace) to re-rank retrieved results based on semantic similarity. Aims to improve precision of top results.

🛠️ Tech Stack
Python

Croma for vector storage and retrieval

Sentence Transformers for embeddings and re-ranking

Jupyter Notebooks for experimentation

***🚀 Getting Started***
To run these notebooks:

Install dependencies:


pip install croma sentence-transformers
Open each notebook in Jupyter or VSCode

Run the cells step by step

***🧠 Notes***
This project is my first hands-on experience with Retrieval-Augmented Generation and Croma. Expect basic code, early-stage learnings, and a few rough edges
