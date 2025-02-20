# Unexpected Behavior with CSS `calc()`
This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS.  The `bug.css` file contains examples of problematic `calc()` usage, while `bugSolution.css` provides corrected versions.  Common issues include inconsistent units and unexpected whitespace within the calculation.

**Key Issues:**
* **Inconsistent Units:** Mixing units within the calculation (e.g., mixing 'px' and '%' without proper consideration) can lead to unexpected behavior.
* **Whitespace Errors:**  Spaces within the calculation where they're not expected (e.g., `100% - 20 px` instead of `100% - 20px`) can break the calculation entirely.
* **Parent Element Size:**  The calculation's result might be unexpected if the parent element doesn't have a defined size (either explicitly or implicitly).