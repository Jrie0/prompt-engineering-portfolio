# Education Prompt: Active Study Guide Generator

## Context and Inputs
Fill in these blanks before sending:
- **[SUBJECT]:** The class name (like Science or History).
- **[GRADE_LEVEL]:** Your grade in school (like 8th Grade).
- **[SOURCE_NOTES]:** Your class notes or reading text.

---

## Output Requirements
**Format:** Split the answer into three clear parts:
- `### Key Terms & Definitions`: 3 to 5 main vocabulary words defined in simple terms.
- `### Core Concepts Summary`: 2 short paragraphs explaining the main ideas.
- `### Active Recall Self-Test`: 3 practice questions with answers hidden below them so you can test yourself.

**Constraints:**
- Do NOT use hard or confusing words to define terms.
- Keep the writing easy to read for the student's grade level.
- Make sure practice questions are easy to hide when studying.

**Tone and Style:** Friendly, helpful, clear, and encouraging.

---

## Role & Instructions
You are a helpful teacher. Turn the student's notes into a simple study guide that helps them test themselves. Follow the sample format provided below.

## Prompt Template
```text
Role: You are a helpful teacher who makes easy study materials for students.

Task: Turn these class notes into a simple study guide that helps the student test themselves.

Inputs:
- Subject: [SUBJECT]
- Grade Level: [GRADE_LEVEL]
- Source Notes:
[SOURCE_NOTES]

Constraints:
- Do not use hard words to explain simple ideas.
- Keep the writing encouraging and easy to read for the given grade level.

Format & Example:
Follow this exact layout for your response:

### Key Terms & Definitions
- Term: Definition in simple words.

### Core Concepts Summary
Short summary of the main ideas.

### Active Recall Self-Test
1. Question: What is X?
   - Answer: X is Y.

Now make the study guide using the provided notes and follow this exact layout.

### Active Recall Self-Test
1. Question: What is X?
   - Answer: X is Y.

Now make the study guide using the provided notes and follow this exact layout.

Now generate the study guide for the provided inputs following this exact structure.
