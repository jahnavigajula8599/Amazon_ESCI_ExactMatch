# Encoder + Reranker Retrieval Pipeline

This repository contains two Jupyter notebooks that demonstrate a complete **hybrid retrieval pipeline** using an encoder model for dense embeddings and a reranker model for refining search relevance. It serves as a lightweight experimentation environment for retrieval, reranking, and baseline RAG-style workflows.

---

## Notebooks Included

### 1. `Encoder+Reranker.ipynb`
End-to-end hybrid retrieval workflow:

- Load and preprocess datasets  
- Generate embeddings using an encoder model  
- Build an in-memory vector store  
- Run similarity search  
- Apply a reranker for improved ranking  
- Compare retrieval quality before vs after reranking  

This is the primary reference notebook for retrieval experimentation.

---

### 2. `Playground.ipynb`
A scratchpad notebook used for:

- Exploring datasets  
- Checking shapes, distributions, missing values  
- Generating small subsets for quick tests  
- Running lightweight experiments before integrating them into the main pipeline  
---

