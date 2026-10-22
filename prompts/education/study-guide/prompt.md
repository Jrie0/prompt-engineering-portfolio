# [Prompt Name] Study Guide Generator

## Overview
**Purpose:** Turns messy student notes or textbook sentences into clear flashcards with self check review questions
**Structure:** CARE
**Technique:** Few-shot
---
## The Prompt

**Context:**
Students studying for classroom tests need straightforward study notes instead of long textbook articles.
**Action:**
Read the material in [NOTES] and generate a study card about the core concept written at a [Target Grade Level].
**`Example 1:**
Input Notes: Photosynthesis happens in plants chloroplasts using sunlight, water, and CO2 to make oxygen and glucose.
Output Concept: Photosynthesis
Simple worded definition: The process plants use to change sunlight, water, and CO2 into sugar food and oxygen.
Study question: What plant cell organelle does photosynthesis take place? (chloroplast)
**`Example 2:**
Input Notes: Newtons first law says that an object at rest stays at rest unless an unbalanced force acts on it.
Output concept: Newtons First Law of Intertia
Simple Definition: Things keep doing what they are doing unless something interferes like a push or pull.
Study question: What is needed to get a stationary object moving. (Unbalanced force)

## Context and Inputs
List the information the user has to supply, written as placeholders:
- **[Notes]:** The raw sentences to summarize and put into a study card.
- **[Target Grade Level]:** Users level of understanding.
---
## Output Requirements
**Format:** A single study card with 3 labeled points. Includes, Core concept, Plain definition, and study question with the answer.
**Constraints:** Don't write intro or concluding text, only match the layout.
**Tone and Style:** Clear, Patient, Educational.

