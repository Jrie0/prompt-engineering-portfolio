# Prompt Engineering Frameworks Reference

## Overview
This document summarizes key prompt engineering frameworks and advanced techniques used throughout this portfolio to optimize AI output quality, consistency, and structure.

---

## 1. Core Frameworks

### R-T-F (Role, Task, Format)
- **Role:** Define who the AI should act as (e.g., Expert Copywriter, Senior Engineer).
- **Task:** Clearly state the action the AI must perform.
- **Format:** Specify how the output should be structured (e.g., Markdown tables, 3 bullet points, under 250 words).

### C-A-R-E (Context, Action, Result, Example)
- **Context:** Background information or constraints.
- **Action:** Specific directives for what the AI needs to create or solve.
- **Result:** Desired final outcome or performance standard.
- **Example:** Sample inputs/outputs to guide formatting and tone.

---

## 2. Advanced Prompting Techniques

### Zero-Shot Prompting
Providing the AI with instructions without giving prior examples. Best for straightforward tasks with explicit structural constraints.

### Few-Shot (Multi-Shot) Prompting
Providing 1 to 3 worked examples within the prompt to demonstrate expected formatting, reasoning, or style before the AI processes the new input.

### Chain-of-Thought (CoT) Prompting
Instructing the model to break complex problems into sequential logical steps (e.g., "Think step-by-step") before providing the final answer. Significantly reduces logical errors in technical, mathematical, or analytical tasks.
