# ROUTING.md — @aikdna/knowledge_management

## When this domain SHOULD be loaded

- Evaluating whether saved or stored information has been processed into usable knowledge
- Diagnosing why a team's knowledge base is not producing better decisions
- Assessing knowledge management practices and information flow
- Determining whether material is raw data, processed information, or actionable knowledge

## When this domain should NOT be loaded

- User asks to search or retrieve specific information (lookup, not judgment)
- User asks to organize files or documents (filing, not judgment)
- Task is about tool selection (which wiki/product to use)
- User wants to create documentation from scratch

## Easily confused tasks (contamination risks)

| Task that looks relevant | Why it should NOT load this domain |
|--------------------------|-----------------------------------|
| "Find the latest sales report" | Information retrieval |
| "Organize our shared drive" | File organization, not knowledge judgment |
| "Which wiki tool should we use?" | Tool evaluation, not knowledge practice |
| "Write documentation for our API" | Documentation creation |

## Recommended test statements

**Should load:**
1. "We have hundreds of saved documents but still make the same mistakes — why?"
2. "Is our team's knowledge actually being used, or just stored?"
3. "How do I know if our knowledge base is producing better decisions?"

**Should skip:**
1. "Search for the Q2 planning document"
2. "Create a folder structure for our team wiki"
3. "Write onboarding docs for new engineers"

## Confidence guidance

- Load without asking when: task is about knowledge quality, utilization, or practice diagnosis
- Always skip when: task is retrieval, organization, or tool selection
