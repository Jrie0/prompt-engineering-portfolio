# Plain-English Code Explainer

**Structure:** Teacher-Student Framework (Summary, Step-by-Step, Key Takeaway)  
**Technique:** Zero-Shot Chain-of-Thought ("Think step-by-step")  
**Output:** A beginner-friendly breakdown of code logic with line-by-line tracing  

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[LANGUAGE]`: The programming language (e.g., Python, JavaScript).
   - `[CODE_SNIPPET]`: The actual code block you want explained.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Ask the model to generate a visual trace diagram or execution table.
- **Want it shorter?** Ask for only the 1-sentence high-level summary.
- **Different context?** Adjust the target audience from "beginner student" to "intermediate developer looking for performance optimizations."

---

## Technical Details

- **Structure:** Custom Teacher-Student breakdown
- **Technique:** Zero-shot Chain-of-Thought
- **Best models:** Gemini, ChatGPT, Claude
- **Placeholders:** 2 placeholders
