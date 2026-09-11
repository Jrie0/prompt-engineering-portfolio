# Prompt Methodology: Active Study Guide Generator

## Design Choices

### 1. Structure Selection
- **Framework:** C-A-R-E (Context, Action, Result, Example) adapted for pedagogical study guide design.
- **Justification:** Passive reading is inefficient for studying. Structuring the prompt around active recall forces the AI to produce materials that engage the learner through testing rather than just summarizing text.

### 2. Technique Selection
- **Technique:** Few-Shot (Multi-Shot) Prompting with explicit question-answer formatting.
- **Justification:** AI models often output passive study summaries instead of test questions. Demonstrating the exact format for active recall questions ensures consistent, high-utility test prep materials.

---

## Evaluation & Testing Results

### Naive vs. Designed Prompt Evaluation

- **Naive Prompt Used:** *"Make a study guide from these notes."*
- **Designed Prompt Score:** 94 / 100
- **Naive Prompt Score:** 48 / 100

### Evaluator Feedback
- **Naive Output:** The naive output simply repeated the notes back in bullet points, creating a wall of text with no active recall elements or vocabulary separation.
- **Designed Output:** The structured prompt separated essential concepts, defined key terms concisely, and built an interactive self-test section that actively engages the student.
