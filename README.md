# learning-rag

My hands-on learning repo for Retrieval-Augmented Generation (RAG): notes, experiments, and small projects.

## Goal
Build a solid, practical understanding of RAG by progressing from core concepts to a working end-to-end pipeline.

## Roadmap
Foundations: embeddings, vector similarity, tokenization basics.
Vector stores: try FAISS, Chroma, or pgvector for storing and retrieving embeddings.
Retrieval: chunking strategies, dense vs sparse retrieval, hybrid search, re-ranking.
Generation: prompt construction, grounding responses in retrieved context.
Evaluation: measuring relevance, faithfulness, and answer quality.
Advanced topics: query rewriting, multi-hop retrieval, agentic RAG.

## Suggested structure
```
learning-rag/
notebooks/   exploratory Jupyter notebooks for each concept
src/         reusable Python modules (chunking, embedding, retrieval, generation)
data/        sample documents and datasets used for experiments
docs/        notes and write-ups on what I have learned
```

## Progress log
Set up environment and dependencies.
Build first basic RAG pipeline.
Experiment with different vector stores.
Try different chunking strategies.
Add evaluation metrics.
