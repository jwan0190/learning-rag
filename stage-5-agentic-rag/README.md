# Stage 5: Agentic RAG

## Learning goals
Learn how an agent differs from a single-shot RAG call: multi-step reasoning, deciding whether retrieval is even needed, rewriting vague queries, and performing multi-hop retrieval for questions that need multiple pieces of evidence.
Understand core agent design patterns such as reflection (self-correction), tool use, planning, and multi-agent collaboration.
Understand reliability and safety concerns for agents: infinite loops, step budgets, destructive actions, and prompt injection through retrieved content.

## Suggested exercise
Write a simple loop (no framework needed at first) where the agent decides after retrieval whether it has enough information to answer, and if not, rewrites the query and retrieves again, up to a fixed step limit.

## Interview questions
Q: What makes a system an agent rather than a simple RAG pipeline with one retrieval step?

Q: Describe a scenario where multi-hop retrieval is necessary to answer a question correctly.

Q: How would you prevent an agent from looping indefinitely or exceeding a reasonable budget of steps and tokens?

Q: If an agent has access to tools that can modify or delete data, how would you guard against destructive actions?

Q: What is prompt injection in the context of RAG, and how could untrusted retrieved documents be used to manipulate an agent's behavior?

Q: When would you choose a single-agent design with multiple tools versus a multi-agent architecture with specialized roles?
