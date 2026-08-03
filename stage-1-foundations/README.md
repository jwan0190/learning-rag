# Stage 1: Foundations

## Learning goals
Understand what embeddings are and how they represent meaning as vectors.
Understand vector similarity (cosine similarity, dot product, Euclidean distance) and why it powers semantic search.
Understand tokenization basics: how LLMs break text into tokens and why context windows are measured in tokens, not words.

## Suggested exercise
Use a library such as sentence-transformers to embed a handful of sentences, then compute cosine similarity between pairs by hand to build intuition for what "semantically close" means.

## Interview questions
Q: What is an embedding, and why do we use vectors instead of raw text to compare meaning?

Q: What is the difference between cosine similarity, dot product, and Euclidean distance when comparing embeddings, and when would you choose one over another?

Q: Two sentences use completely different words but mean the same thing. Would a keyword search and a vector search behave differently here? Why?

Q: What is a token, and why does an LLM's context window get measured in tokens rather than characters or words?

Q: Why might two embedding models produce different similarity scores for the same pair of sentences?

Q: What happens if you compare embeddings produced by two different embedding models? Is that safe to do?
