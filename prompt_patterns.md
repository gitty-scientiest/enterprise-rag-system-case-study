# Prompt & Instruction Engineering Patterns

## Grounded Answering Pattern
Answer strictly using the provided context.
If the information is not available, respond with:
"I do not have sufficient information to answer this question."

## Role-Aware Prompting
You are an assistant supporting enterprise users.
Adapt responses based on the user's role and context.


## Hallucination Mitigation
- Explicit refusal instructions
- Confidence-based response control
- Context-only answering enforcement

---

## Iterative Prompt Optimization
1. Write baseline instructions
2. Test responses
3. Identify hallucinations or ambiguity
4. Refine instructions
5. Repeat until stable behavior is achieved
