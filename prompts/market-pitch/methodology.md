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
| Naive baseline | 0 | No structure, just a straight up bare question. |
| Version 1 | 100 | More in detail prompt with RTF structure.  |
| Final | 100 |
**What testing showed:** The Naive prompt gave me a long paragraph with super confusing terms. Definitely not readable/speak able in 30 seconds. That's why I added a word limit and 4 part structure to make the pitch easy to say in 30 seconds.
**What I learned:** Limiting buzzwords makes the AI actually explain something through instead of using a shortcut.
---
## Strengths and Limitations
**Works well when:** Pitching products such as apps, objects, etc.
**Struggles when:** Describing more complex systems or technical products.
**Would improve next:** Add a bullet point that shows the price and even savings.
