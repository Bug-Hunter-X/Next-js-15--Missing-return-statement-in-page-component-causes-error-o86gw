# Next.js 15: Missing return statement in page component

This repository demonstrates a common error in Next.js 15 applications where a page component is missing a `return` statement, leading to unexpected behavior and errors.

## Bug
The `pages/about.js` file is missing a `return` statement in its component. This results in a runtime error when attempting to navigate to the `/about` page.

## Solution
Adding a `return` statement, even if it's just returning null, will resolve the issue.