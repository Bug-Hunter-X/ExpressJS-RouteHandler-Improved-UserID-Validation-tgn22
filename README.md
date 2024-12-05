# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  Specifically, the code attempts to parse a user ID as an integer without validating if it's actually a number. This can lead to crashes or unexpected behavior if a non-numeric ID is supplied.

The `bug.js` file contains the buggy code.  The `bugSolution.js` file provides a corrected version with comprehensive error handling.