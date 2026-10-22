# Design Methodology: Study Guide generator
## Design Goal
To take important concepts from complex notes or articles and turns them into a straightforward study card with study questions.
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** CARE
**Why this structure fits my task:**
- Context shows the setting/goal.
- Result with examples gives the AI a blueprint.
**Technique I used:** Few-Shot
**Why this technique fits my task:**
Giving two examples shows the model how to format the study card and question the same each time.
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Context | Students studying for a test | Focuses the Model |
| Action | Take main concept and make study cards | Directs the Model |
| Examples | Two formatted study card examples | Shows the structure and tone needed. |
| Results | Three point card layout | Locks in the format |
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
