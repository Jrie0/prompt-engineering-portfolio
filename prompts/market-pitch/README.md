# Product Pitch Generator
> *Turns product specifications into a 30 second elevator pitch.*
## Overview
This prompt takes product details and turns them into a spoken sales pitch under 90 words. It avoids buzzwords and rambling by focusing on the customers problem, the solution, and the call to action.
**Best for:**
- Writing a 30 second elevator pitch.
- Explaining a new app or product.
- Getting rid of buzzwords from marketing pitch.
**Structure:** RTF with constraints.
**Technique:** Zero-Shot
**Output:** A 4 part script. Hook, solution, advantage, call to action under 90 words.
---
## Quick Start
1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
- `[Product Details]`: Paste your product name, features, or benefit.
- `[Target Audience]`: Put who the product is made for. 
3. Paste it into your AI model of choice and run it.
4. Review the output and adapt it to what you need.
---
## Examples
See the [`examples/`](./examples/) folder for filled-in demonstrations showing the
prompt and the resulting output.
---
## Customization Tips
- **Want more detail?** Add a constraint asking for price details in the solution sentence.
- **Want it shorter?** Ask for a single sentence social media ad instead of a full speech.
- **Different context?** Swap the target audience from customers to investors.
---
## Technical Details
- **Structure:** RTF with constraints.
- **Technique:** Zero-shot
- **Best models:** Gemini, ChatGPT, Claude
- **Placeholders:** [Product Details], [Target Audience]
