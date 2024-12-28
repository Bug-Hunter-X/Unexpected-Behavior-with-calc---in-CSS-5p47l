# Unexpected Behavior with calc() in CSS
This repository demonstrates two uncommon errors that can occur when using the `calc()` function in CSS:

1. **Inconsistent Units:** Using incompatible units within a single `calc()` expression can lead to unexpected results. Percentages and absolute units (like pixels or ems) are often the source of confusion.
2. **Missing Spaces:** Forgetting spaces around the operators (+, -, *, /) inside the `calc()` function results in a syntax error, preventing the CSS from working correctly. 

The `bug.css` file showcases these errors, while `bugSolution.css` provides the corrected versions.  Careful attention to unit compatibility and proper spacing are crucial for reliably using the `calc()` function.