# Stage 2: Vector Stores and Basic Retrieval

## Learning goals
Build your first end-to-end RAG pipeline: load documents, split into chunks, embed them, store them in a vector database, and retrieve the top-k most relevant chunks for a query.
Get hands-on with at least one vector database such as FAISS, Chroma, or pgvector, and understand how they index and search vectors efficiently.

## Suggested exercise
Take a small set of documents you know well, build a minimal pipeline that answers questions grounded in those documents, and manually inspect which chunks got retrieved for a few sample queries.

## Interview questions
Q: Walk me through the components of a basic RAG pipeline, from raw documents to a final answer.

Q: What is the role of a vector database in RAG, and how does it differ from a traditional relational database?

Q: How does approximate nearest neighbor search (e.g. HNSW) trade off speed and accuracy compared to exact nearest neighbor search?

Q: If your retriever returns irrelevant chunks, what parts of the pipeline would you inspect first?

Q: How would you decide how many chunks (top-k) to retrieve for a given query?

Q: What happens to answer quality if the vector database returns zero relevant results? How should the system handle that case?
