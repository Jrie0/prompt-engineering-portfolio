# Design Methodology: Product Marketing Pitch Generator

## Design Goal
Create a structured prompt that generates clear and persuasive product marketing pitches tailored to a specific audience without relying on overused hype words.

---

## Design Approach: Structure and Technique

**Structure I used:** Modified R-T-F (Role, Task, Inputs, Constraints, Format).

**Why this structure fits my task:**
- Assigning a clear **Role** sets a professional copywriter tone immediately.
- Adding strict **Constraints** prevents common AI marketing slop like buzzwords and unverified claims.

**Technique I used:** Zero-shot.

**Why this technique fits my task:**
Marketing pitches follow standard structural rules. Providing specific format guidelines and constraints gives the AI enough direction without needing full worked examples.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Expert product marketing strategist | Establishes professional authority and persuasive writing style. |
| Task | Draft a concise, high-converting product marketing pitch | Defines the core goal of the prompt clearly. |
| Inputs | Product Name, Target Audience, Key Benefit, Tone | Ensures the pitch is customized to a specific product and user demographic. |
| Constraints | Word limit (<250 words), anti-buzzword rule, no unverified claims | Keeps copy concise, believable, and grounded. |
| Format | 3-part layout (Hook, Solution, Call to Action) | Guarantees a classic, high-converting copy structure. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Write a marketing pitch for the HydroGlow Insulated Water Bottle for busy professionals.
