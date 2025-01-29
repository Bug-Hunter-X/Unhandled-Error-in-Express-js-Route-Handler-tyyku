# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: a lack of robust error handling.  The provided code attempts to retrieve a user based on their ID. However, it fails to handle cases where the ID is invalid (not a number) or doesn't exist, resulting in unexpected behavior or silent failure.

The `bug.js` file contains the erroneous code, while `bugSolution.js` offers a corrected version with improved error handling.