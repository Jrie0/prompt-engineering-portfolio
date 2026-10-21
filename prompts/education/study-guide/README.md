# Study Guide Generator
> *Turns classroom notes into focused study cards with review questions.*
## Overview
This prompt turns school notes or textbook snippets into clear study cards. It limits information overload by keeping only the main concept, a simple definition, and study question. Its good for people studying for tests.
**Best for:**
- Making flashcards before tests.
- Summarizing notes simply.
- Testing yourself with review questions.
**Structure:** CARE
**Technique:** Few-shot
**Output:** A structured study card with a core topic, simple definition, and quiz question.
---
## Quick Start
1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- `[Notes]`:Paste your notes or textbook material.
- `[Target Grade Level]`: Enter your grade of best understanding.
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.
---
## Examples
See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.
---
## Customization Tips
- **Want more detail?** Ask the prompt to add a real world analogy under the definition.
- **Want it shorter?** Take away the quiz question to get only the definition card.
- **Different context?** Change the target level to high school.
---
## Technical Details
- **Structure:** CARE
- **Technique:** Few-shot
- **Best models:** Chat GPT, Gemini, Claude
- **Placeholders:** 2 placeholders, [Notes], [Target Grade Level]
