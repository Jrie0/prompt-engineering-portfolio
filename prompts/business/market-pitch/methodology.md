# Design Methodology: Product Marketing Pitch Generator

## Design Goal
Make a simple prompt that writes short, convincing sales pitches for products without using fake hype or buzzwords.

---

## Design Approach: Structure and Technique

**Structure I used:** Modified R-T-F (Role, Task, Inputs, Constraints, Format).

**Why this structure fits my task:**
- Giving the AI a clear **Role** helps it sound like a professional marketer right away.
- Adding strict **Constraints** stops the AI from using annoying marketing buzzwords or making fake health claims.

**Technique I used:** Zero-shot.

**Why this technique fits my task:**
Sales pitches usually follow a basic pattern. Giving clear rules and layout steps gives the AI enough help without needing a full sample example.

---

## Part-by-Part Justification

| Part | What I put here | Why the prompt needs it |
|------|-----------------|-------------------------|
| Role | Expert product marketing strategist | Helps the AI write professionally and persuasively. |
| Task | Draft a concise product marketing pitch | Tells the AI exactly what job to do. |
| Inputs | Product Name, Target Audience, Key Benefit, Tone | Gives the AI the exact details about the product to write about. |
| Constraints | Under 250 words, no buzzwords, no fake claims | Keeps the writing short, honest, and easy to read. |
| Format | 3-part layout (Hook, Solution, Call to Action) | Makes sure the pitch has a clear beginning, middle, and ending. |

---

## Testing and Iteration

**Baseline I compared against:**
```text
Write a marketing pitch for the HydroGlow Insulated Water Bottle for busy professionals.
Write a marketing pitch for the HydroGlow Insulated Water Bottle for busy professionals.
