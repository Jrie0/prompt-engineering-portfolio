# Product Marketing Pitch Generator

**Structure:** Modified R-T-F (Role, Task, Inputs, Constraints, Format)  
**Technique:** Zero-Shot  
**Output:** A 3-paragraph marketing pitch under 250 words with no buzzwords  

---

## Quick Start

1. Open [`prompt.md`](./prompt.md) and copy the template.
2. Replace the placeholders:
   - `[PRODUCT_NAME]`: The name of your product or service.
   - `[TARGET_AUDIENCE]`: Who you are selling to.
   - `[KEY_BENEFIT]`: The main benefit.
   - `[TONE]`: Preferred tone of voice (e.g., energetic, professional).
3. Paste it into your AI Chatbot of your choosing and run it.
4. Check the output and use it for what you need.

---

## Examples

See the [`examples/`](./examples/) folder for filled-in demonstrations showing the prompt and the resulting output.

---

## Customization Tips

- **Want more detail?** Ask the model to add a bulleted list of 3 secondary features.
- **Want it shorter?** Ask for a maximum of 2 paragraphs or under 150 words.
- **Different context?** Change the targeted audience to B2B professionals to shift from consumer pitch to investor pitch.

---

## Technical Details

- **Structure:** Modified R-T-F framework
- **Technique:** Zero-shot
- **Best models:** Gemini, ChatGPT, Claude
- **Placeholders:** 4 placeholders
