# Stage 3: Chunking and Retrieval Strategies

## Learning goals
Experiment with different chunking strategies (fixed length, paragraph-based, semantic chunking) and observe how they affect retrieval quality.
Understand the difference between dense (vector) retrieval and sparse (keyword, e.g. BM25) retrieval, and how hybrid search combines both.
Understand reranking: why retrieving a larger candidate set and then reordering it with a cross-encoder often beats retrieving a small top-k directly.

## Suggested exercise
Take the same document set from Stage 2 and try at least three chunk sizes or splitting strategies. Compare retrieved results for the same queries and note when smaller or larger chunks help or hurt.

## Interview questions
Q: What are the trade-offs between small chunks and large chunks when splitting documents for retrieval?

Q: How would you choose a chunk overlap size, and why is some overlap usually helpful?

Q: When would keyword-based search (like BM25) outperform vector search, and vice versa?

Q: What is hybrid search, and how do you combine scores from a keyword search and a vector search?

Q: What problem does reranking solve that retrieval alone does not?

Q: A user asks a question that references an exact product ID or code. How does this change your retrieval strategy compared to a general semantic question?
