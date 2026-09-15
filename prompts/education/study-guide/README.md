# Active Study Guide Generator

**Structure:** C-A-R-E Framework (Context, Action, Result, Example)  
**Technique:** Few-Shot Prompting  
**Output:** A simple study guide with definitions, a short summary, and practice questions  

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[SUBJECT]`: The topic name (like Science or History).
   - `[GRADE_LEVEL]`: The school grade level (like 8th Grade or High School).
   - `[SOURCE_NOTES]`: The notes or textbook text you want to study.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Ask the AI to add 3 more study questions.
- **Want it shorter?** Ask for only the vocabulary definitions.
- **Different context?** Ask the AI to turn the questions into flashcard format.

---

## Technical Details

- **Structure:** C-A-R-E framework
- **Technique:** Few-shot
- **Best models:** Gemini, ChatGPT, Claude
- **Placeholders:** 3 placeholders
