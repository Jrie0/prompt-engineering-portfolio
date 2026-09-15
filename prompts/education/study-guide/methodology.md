# Design Methodology: Active Study Guide Generator

## Design Goal
Turn plain class notes into an easy study guide that helps students test themselves before an exam.

---

## Design Approach: Structure and Technique

**Structure I used:** C-A-R-E Framework (Context, Action, Result, Example).

**Why this structure fits my task:**
- Setting the **Context** makes sure the study guide is easy to read for the right grade level.
- Giving a clear **Action** stops the AI from just copying the notes back to you.

**Technique I used:** Few-Shot Prompting.

**Why this technique fits my task:**
AI models usually just summarize notes. Giving it a short example shows it exactly how to write practice questions with answers.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Educational designer | Helps the AI write like a good teacher. |
| Inputs | Subject, Grade Level, Source Notes | Gives the AI the exact material it needs to turn into a study guide. |
| Constraints | No circular definitions and simple tone | Stops the AI from using hard words to explain simple ideas. |
| Few-Shot Example | Worked question and answer sample | Forces the AI to make a real practice test instead of just a big block of text. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Make a study guide from these notes:
Light is a form of energy that travels in waves. Refraction is when light bends as it passes from one material into another, like from air into water. Snell's Law helps calculate how much the light bends based on the index of refraction of the materials.
