# CSS `calc()` Function Unexpected Behavior

This repository demonstrates an uncommon error related to the CSS `calc()` function.  The issue occurs when subtracting a fixed length from a percentage value within `calc()`, potentially resulting in a negative width under certain circumstances.

The `bug.css` file contains the problematic code. The `bugSolution.css` offers a solution to prevent this behavior.

This is a subtle error that may not be immediately apparent, highlighting the importance of testing CSS across different viewport sizes and browser versions.