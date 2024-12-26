# Uncommon HTML Errors

This repository demonstrates two uncommon errors that can occur when working with HTML:

1. **Attempting to access a non-existent element:**  This often results in a silent failure, making it difficult to debug.  The code attempts to access an element with the ID "myDiv2", which doesn't exist in the HTML. This can lead to unexpected behavior in the rest of your code.
2. **Incorrect use of `innerHTML`:** The code attempts to assign a number to the `innerHTML` property instead of a string. While some browsers might handle this gracefully, it's a potential source of unexpected behavior and is generally bad practice.

The `bug.html` file contains the buggy code. The `bugSolution.html` provides a corrected version.