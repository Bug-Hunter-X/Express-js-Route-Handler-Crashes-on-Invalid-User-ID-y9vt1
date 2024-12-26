# Express.js Route Handler Crash on Invalid User ID

This repository demonstrates a common error in Express.js applications where a route handler crashes when it receives an invalid user ID.  The `bug.js` file shows the problematic code, failing to handle the case where a user with the provided ID does not exist. The `bugSolution.js` file offers a corrected version that gracefully handles this scenario, avoiding application crashes.

## Setup

1. Clone this repository.
2. Run `npm install express`
3. Run the code using `node bug.js` or `node bugSolution.js` (depending on which file you want to run).