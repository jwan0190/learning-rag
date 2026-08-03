# Stage 4: Evaluation

## Learning goals
Learn to measure RAG quality objectively instead of relying on gut feeling: retrieval relevance, answer faithfulness (grounding), and answer relevance to the original question.
Build a small evaluation set of question and answer pairs so you can measure the effect of any pipeline change.
Understand common failure modes: hallucination when context is missing, and the lost in the middle problem where relevant information placed in the middle of a long context gets ignored by the model.

## Suggested exercise
Write 10 to 15 question and answer pairs based on your document set, including a few questions that should not be answerable from the documents. Run your pipeline against them and score faithfulness and relevance by hand.

## Interview questions
Q: How do you evaluate whether a RAG system's retrieval step is working well, separate from the generation step?

Q: What does it mean for an answer to be faithful or grounded, and how would you detect when it is not?

Q: A RAG system is hallucinating confidently wrong answers. Where would you start debugging, and why?

Q: What is the lost in the middle problem, and how might you mitigate it when constructing the prompt context?

Q: How would you build a regression test suite for a RAG pipeline so future changes do not silently degrade quality?

Q: What is the difference between offline evaluation with a fixed test set and online evaluation using real user feedback?
