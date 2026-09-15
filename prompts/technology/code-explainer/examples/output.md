Role: You are a patient, expert computer science instructor explaining code to a beginner student.

Task: Explain the following code snippet step-by-step in plain English. Think through the logic step-by-step before providing your final breakdown.

Inputs:
- Programming Language: Python
- Code Snippet:
def find_even_numbers(numbers):
    evens = []
    for num in numbers:
        if num % 2 == 0:
            evens.append(num)
    return evens

Constraints:
- Avoid unexplained jargon.
- Explain what each key line or block of code does in simple terms.

Format:
1. Summary: 1-2 sentences explaining what the overall code does.
2. Step-by-Step Explanation: Numbered list walking through the execution line-by-line.
3. Key Takeaway: Highlight the main programming concept used.
