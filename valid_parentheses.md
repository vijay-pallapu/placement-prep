\# Valid Parentheses – Explanation



Approach:

\- Use a stack to track opening brackets.

\- Map closing brackets to their opening ones.

\- For each character:

&nbsp; - If opening → push.

&nbsp; - If closing → check top of stack, if mismatch → False.

\- At end, stack must be empty → True.



Time Complexity: O(n)

Space Complexity: O(n)



