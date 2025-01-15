# Tcl Unexpected Comparison Behavior
This repository demonstrates an unexpected behavior in Tcl when comparing values.  The `badproc` procedure shows incorrect logic in an `if` statement that affects the return value under certain conditions. The solution provides a corrected version of the procedure with improved comparison logic.

## Bug
The original `badproc` procedure uses `==` for comparison, which can lead to unexpected results when dealing with numbers or strings. The incorrect conditional check in the `if` statement results in the function not returning the expected value.

## Solution
The solution introduces a revised `badproc` procedure with a more robust comparison that addresses these issues. The corrected procedure uses explicit type checking when appropriate to prevent unintended comparisons.