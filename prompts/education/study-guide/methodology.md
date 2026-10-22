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
| Naive baseline | 0 | Bare question, gave me long paragraphs. |
| Version 1 | 100 | Added the CARE structure without examples. |
| Final | 100 | [notes] |
**What testing showed:** The Naive prompt gave me long complex sentences, but the few shot examples forced the AI to give give me the nice card layout.
**What I learned:** Showing examples of how you want information is better than describing the information you want without them.
---
## Strengths and Limitations
**Works well when:** Summarizing science, history, and vocab concepts with definitions.
**Struggles when:** Going through large documents with multiple topics.
**Would improve next:** Add a multiple choice quiz.
