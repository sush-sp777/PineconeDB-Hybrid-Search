# Pinecone Hybrid Search Practice

- This repository contains a practical implementation of Pinecone Hybrid Search using
LangChain, HuggingFace Embeddings, and BM25 sparse encoding.
---

- Pinecone is a vector database that supports hybrid search by combining dense semantic
embeddings with sparse keyword signals.
- This example demonstrates how to create a hybrid index in Pinecone, generate dense (HuggingFace) and sparse (BM25) vectors,
store them together, and perform a hybrid retrieval using Reciprocal Rank Fusion (RRF).
