# CSS calc() Gotchas
This repo demonstrates two potential issues when using the `calc()` function in CSS:

1. **Unit Incompatibility:** Mixing incompatible units (like `%` and `em`) within a `calc()` expression can lead to unexpected results or parsing errors.
2. **Missing Spaces:**  Forgetting spaces between operators and operands inside `calc()` expressions will also cause errors.

The `bug.css` file showcases incorrect usage. The `bugSolution.css` provides the corrected version.