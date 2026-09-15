# Design Methodology: Plain-English Code Explainer

## Design Goal
Allow beginner computer science students to understand programming logic line-by-line without getting overwhelmed by unexplained technical buzzwords.

---

## Design Approach: Structure and Technique

**Structure I used:** Custom Teacher-Student Structure (Summary, Step-by-Step Breakdown, Key Takeaway).

**Why this structure fits my task:**
- Starting with a high-level **Summary** provides a quick mental map of what the code achieves before diving into syntax.
- Isolating a **Key Takeaway** reinforces fundamental computer science concepts for long-term learning.

**Technique I used:** Zero-Shot Chain-of-Thought ("Think step-by-step").

**Why this technique fits my task:**
Code execution relies on sequential logic. Instructing the AI to "think through the logic step-by-step" forces it to trace execution paths line-by-line rather than making assumptions or skipping lines.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Patient CS instructor explaining to a beginner | Gives an encouraging tone without intimidating language. |
| Task & Instruction | Explain code logic step-by-step | Explicitly starts Chain-of-Thought reasoning. |
| Inputs | Programming Language and Code Snippet | Gives the important context the AI needs to process the code. |
| Constraints | Avoid unexplained buzzwords | Keeps the model from using complex computer science terms without explaining them. |
| Format | 3-part layout (Summary, Breakdown, Takeaway) | Gives a scannable structure for student review. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Explain what this code does:
def find_even_numbers(numbers):
    evens = []
    for num in numbers:
        if num % 2 == 0:
            evens.append(num)
    return evens
