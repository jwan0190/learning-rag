# learning-rag

My hands-on learning repo for Retrieval-Augmented Generation (RAG): notes, experiments, and small projects.

## Goal
Build a solid, practical understanding of RAG by progressing from core concepts to a working end-to-end pipeline, and be ready to talk about it confidently in interviews.

## Learning stages
Each stage below has its own folder with learning goals, a suggested exercise, and a set of related interview questions.

[Stage 1: Foundations](./stage-1-foundations/README.md) covers embeddings, vector similarity, and tokenization basics.
[Stage 2: Vector Stores and Basic Retrieval](./stage-2-vector-stores/README.md) covers building a first end-to-end RAG pipeline.
[Stage 3: Chunking and Retrieval Strategies](./stage-3-retrieval-strategies/README.md) covers chunking choices, hybrid search, and reranking.
[Stage 4: Evaluation](./stage-4-evaluation/README.md) covers measuring retrieval and answer quality, and debugging hallucinations.
[Stage 5: Agentic RAG](./stage-5-agentic-rag/README.md) covers multi-step agents, tool use, and safety concerns.

## Suggested structure
```
learning-rag/
stage-1-foundations/          learning notes + interview questions
stage-2-vector-stores/        learning notes + interview questions
stage-3-retrieval-strategies/ learning notes + interview questions
stage-4-evaluation/           learning notes + interview questions
stage-5-agentic-rag/          learning notes + interview questions
notebooks/                    exploratory Jupyter notebooks for each concept
src/                          reusable Python modules (chunking, embedding, retrieval, generation)
data/                         sample documents and datasets used for experiments
```

## Progress log
Set up environment and dependencies.
Build first basic RAG pipeline.
Experiment with different vector stores.
Try different chunking strategies.
Add evaluation metrics.
Build a simple agentic RAG loop.
