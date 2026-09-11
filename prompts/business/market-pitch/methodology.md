# Prompt Methodology: Product Marketing Pitch Generator

## Design Choices

### 1. Structure Selection
- **Framework:** R-T-F (Role, Task, Format) extended with explicit Constraints and Inputs.
- **Justification:** Giving the AI a clear role (Expert Marketing Strategist) grounds its tone, while setting strict constraints (3 paragraphs, under 250 words, avoiding buzzwords) prevents generic, wordy fluff.

### 2. Technique Selection
- **Technique:** Zero-Shot with Structural Constraints.
- **Justification:** Marketing pitches follow a standard Hook-Solution-CTA structure. Clear structural constraints provide sufficient guidance without needing full worked examples, keeping the execution quick and versatile across different products.

---

## Evaluation & Testing Results

### Naive vs. Designed Prompt Evaluation

- **Naive Prompt Used:** *"Write a marketing pitch for a product."*
- **Designed Prompt Score:** 92 / 100
- **Naive Prompt Score:** 45 / 100

### Evaluator Feedback
- **Naive Output:** The naive prompt produced a generic, overly hyped block of text with buzzwords like "game-changer" and lacked a clear target audience focus.
- **Designed Output:** The structured prompt generated a clean, persuasive 3-paragraph copy with a strong hook, clear benefits, and a compelling Call to Action, perfectly adhering to the word limit and tone constraints.
