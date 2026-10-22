# Design Methodology: Product Pitch Generator
## Design Goal
To convert product specs into a 30 second persuasive elevator speech.
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** RTF with constraints and format
**Why this structure fits my task:**
- The role sets a professional tone.
- Constraints keep it simple and compact and free of common buzzwords.
**Technique I used:** Zero-shot
**Why this technique fits my task:**
The goal is very straightforward and relies on constraints rather than following basic styles.
---
## Part-by-Part Justification
Justify each part of your prompt: what it is, what goes in it, and why the prompt
needs it. If your prompt is technique-driven and short (for example zero-shot
chain-of-thought), justify the technique and the few parts you do have instead.
| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Professional Salesman | Instructs the AI of the setting and tone |
| Task| Turn specifications into a pitch | Tells the AI what to build |
| Constraints | 75-90 words | Keeps the speech easy to understand and quick |
| Format | Four numbered sections | Makes the pitch easy to read in order |
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
