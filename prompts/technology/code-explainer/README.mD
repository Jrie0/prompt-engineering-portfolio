# Simple worded Code Explainer
> *Brekas down computer code into line by line explanation for beginners.*
## Overview
This prompt takes any bit of code and turns it into an easy explanation without complex words. It helps people understand how their code runs line by line without any confusing words.
**Best for:**
- Explaining homework code line by line.
- Simplifying error messages or syntax.
- Learning programming basics like variables.
**Structure:** RTF with reasoning and constraints.
**Technique:** Zero-shot chain of thought.
**Output:** 3 parts under 150 words with a summary, steps, and result.
---
## Quick Start
1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- `[CODE]`
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.
---
## Examples
See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.
---
## Customization Tips
- **Want more detail?** Take away the 150 word limit and ask for more in depth explanation.
- **Want it shorter?** Ask for the 1 sentence summary and the final output print.
- **Different context?** Change the target reading level from 8th grade to high school freshamn.
---
## Technical Details
- **Structure:** RTF with constraints and format
- **Technique:** Zero-shot chain-of-thought
- **Best models:** Gemini, ChatGPT, Claude
- **Placeholders:** [CODE]
