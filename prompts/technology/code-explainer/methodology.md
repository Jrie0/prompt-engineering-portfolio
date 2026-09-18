---

### 2. Technology Category — `methodology.md`

In GitHub, go to `prompts/technology/code-explainer/methodology.md`, click the pencil icon, and paste this in:

```markdown
# Design Methodology: Plain-English Code Explainer

## Design Goal
Help new programming students understand lines of code without getting confused by hard technical words.

---

## Design Approach: Structure and Technique

Structure I used: Custom Teacher-Student Structure (Summary, Step-by-Step Breakdown, Key Takeaway).

Why this structure fits my task:
- Starting with a Summary gives students a quick idea of what the code does before looking at lines.
- Adding a Key Takeaway helps students remember the main coding idea.

Technique I used: Zero-Shot Chain-of-Thought ("Think step-by-step").

Why this technique fits my task:
Code runs line by line in order. Telling the AI to "think step-by-step" forces it to trace the code slowly instead of skipping steps.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Patient computer science teacher for beginners | Keeps the tone helpful and friendly so students do not feel confused. |
| Task & Instruction | Explain code step-by-step | Forces the AI to slow down and explain line by line. |
| Inputs | Programming Language and Code Snippet | Shows the AI the exact code it needs to explain. |
| Constraints | Avoid hard Language | Stops the AI from using complex words without explaining what they mean. |
| Format | 3-part layout (Summary, Breakdown, Takeaway) | Keeps the final answer neat and easy to read. |

---

## Testing and Iteration
