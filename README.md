# Next.js Navigation Bug

This repository demonstrates a common bug in Next.js applications where navigation links fail to work correctly, leading to 404 errors.

## Bug Description

A simple Next.js application is set up with two pages: `index.js` (the home page) and `about.js`.  A link on the home page is intended to navigate to the `about.js` page. However, clicking the link results in a 404 error.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the home page in your browser.
5. Click the link to the about page.
6. Observe the 404 error.

## Solution

The bug is resolved by ensuring that both pages are correctly exported and the path of the link is accurate.  The solution is provided in `bugSolution.js`.

## Additional Notes
This bug is commonly caused by issues in the page file structure, incorrect naming of the files, or mistakes in the Link component usage within Next.js.