# Design Methodology: Simple Language Code Explainer
## Design Goal
Used to break down computer code into a simple explanation for beginner students without any confusing terms.
---
## Design Approach: Structure and Technique
Explain the two design choices behind your prompt and why they fit the task.
**Structure I used:** RTF with constraints and format.
**Why this structure fits my task:**
- Sets a teacher role tone so its beginner friendly.
- Adding Constraints and Format keeps the AI easy to understand and compact.
**Technique I used:** Zero shot chain of thought.
**Why this technique fits my task:**
Tracing code needs step by step logic so the model doesn't make mistakes or miss something.
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
| Naive baseline | 0 | No clarity, frame, requirements, etc.  | 
| Version 1 | 100 | RTF structure gave it role, task, and format. (also contraints and reasoning) | 
| Final | 100 | 
**What testing showed:** The Naive prompt got zero because it had no detail or requirements at all. I changed that by adding the RTF structure which got the prompt to 100 percent immediately even with fairly brief instructions.
**What I learned:** You can tailor prompts to give you literally anything and in the way that helps you best.
---
## Strengths and Limitations
**Works well when:** When explaining SHORTER scripts. It needs to go in to detail when dealing with really long scripts.
**Struggles when:** It needs to go in to detail when dealing with really long more complex scripts.
**Would improve next:** Explain error messages better.
