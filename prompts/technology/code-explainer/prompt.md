# [Prompt Name] Plain English Code Explainer

## Overview
**Purpose:** Breaks down confusing code into simple explanations without big unfamiliar words.
**Structure:** R-T-F
structure," then list the parts it breaks into, for example: Context, Task,
Constraints, Format.]
**Technique:** Zero-Shot chain of thought
---
## The Prompt

**Role:**
Act as a computer science teacher who is really good at explaining things clearly for beginners.
**Task:**
Analyze given code and explain what it gets done and simplify what is does line by line.
**Reasoning:**
Before giving final response, go through the following step by step.
1. Find all variables, data types, and operators.
2. Follow the execution order line by line top to bottom.
3. Give real world equivalents for complex terminology. 
---
## Context and Inputs
List the information the user has to supply, written as placeholders:
- **The code that needs to be explained.

  
## Output Requirements
**Format:** A 3 section response with 1 sentence summary, a line by line explanation, and final output line.
**Constraints:** Under 150 words, no complex technical terms.
**Tone and Style:** Supportive, patient, conversational at an 8th grade reading level.
---
