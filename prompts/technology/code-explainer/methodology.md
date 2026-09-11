# Prompt Methodology: Plain-English Code Explainer

## Design Choices

### 1. Structure Selection
- **Framework:** Custom Teacher-Student Framework (Role, High-Level Summary, Line-by-Line Breakdown, Key Takeaway).
- **Justification:** Code explanations often overwhelm beginners when they drop straight into line-by-line syntax. Structuring the prompt to demand an initial summary before diving into details gives learners a mental map before dealing with technical syntax.

### 2. Technique Selection
- **Technique:** Zero-Shot Chain-of-Thought (Asking the model to reason step-by-step through the code logic before summarizing).
- **Justification:** Technical code analysis requires step-by-step logical verification. Forcing the AI to walk through execution line-by-line prevents it from skipping steps or hallucinating what a code snippet does.

---

## Evaluation & Testing Results

### Naive vs. Designed Prompt Evaluation

- **Naive Prompt Used:** *"Explain what this code does."*
- **Designed Prompt Score:** 95 / 100
- **Naive Prompt Score:** 50 / 100

### Evaluator Feedback
- **Naive Output:** The naive output used heavy computer science jargon without explanations and jumped around between different parts of the code without a clear sequence.
- **Designed Output:** The structured prompt delivered a clear, beginner-friendly walkthrough that defined technical terms as they appeared and provided a useful summary for context.
