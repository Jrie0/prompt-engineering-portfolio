# Design Methodology: Simple Language Code Explainer
## Design Goal
Used to break down computer code into a simple explanation for beginner students without any confusing terms.
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** RTF with constraints and format.
**Why this structure fits my task:**
- Sets a teacher role so its beginner friendly.
- Adding Constraints and Format keeps the AI easy to understand and compact.
**Technique I used:** Zero shot chain of thought.
**Why this technique fits my task:**
Tracing code needs step by step logic so the model doesn't make mistakes and hallucinate. 
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Beginner CS teacher | Sets a understanding and teaching tone. |
| Task | Analyze a bit code and explain what each line does | Explains the goal clearly |
| Reasoning | Step by step tracing | Stops errors or skipped steps |
| Constraints | 8th grade reading level, 150 word cap | Keeps simple words and limits lengthy sentences. |
| Format | Summary, line by line list and final output. | Keeps clean layout |
---
## Testing and Iteration
Test your prompt against a naive baseline, a plain version of the same request with
no deliberate structure or technique, and refine it based on what you see.
**Baseline I compared against:**
```
[Your plain, naive version of the same request]
```
| Version | Result / score | What changed |
|---------|----------------|--------------|
| Naive baseline | [result] | [notes] |
| Version 1 | [result] | [notes] |
| Final | [result] | [notes] |
**What testing showed:** [In your own words, how your designed prompt performed
compared to the baseline, and what you changed as a result.]
**What I learned:** [What this taught you about prompt design.]
---
## Strengths and Limitations
**Works well when:** [The conditions where this prompt performs best.]
**Struggles when:** [Where it breaks down, and why.]
**Would improve next:** [What you would refine with more time.]
