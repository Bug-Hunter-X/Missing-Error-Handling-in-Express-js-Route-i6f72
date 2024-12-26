# Express.js Route Error Handling Bug

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling.  The `bug.js` file contains a route that fetches a user by ID.  It fails to handle cases where the user ID is invalid (e.g., not a number), leading to potential crashes or unexpected behavior.

The `bugSolution.js` file provides a corrected version with robust error handling, showcasing best practices for handling invalid inputs in Express.js routes.  This includes checking for the existence of the user and handling cases where the ID is not a number or the user is not found.