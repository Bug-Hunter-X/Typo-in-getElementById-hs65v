# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle yet common error in JavaScript when interacting with the HTML DOM. The bug showcases a typo in the `getElementById` method, which causes the code to fail silently without throwing an error.

## Bug Description

The HTML file contains a simple `div` element. The JavaScript code attempts to modify the content of this `div`, but it uses `getElementByIdx` instead of `getElementById`, causing the modification to fail without any obvious indication.

## How to Reproduce

1. Clone the repository.
2. Open `bug.html` in a web browser.
3. Observe that the text within the `div` remains unchanged, indicating that the code failed to modify it.

## Solution

The solution involves correcting the typo in the JavaScript code. The `getElementByIdx` should be replaced with `getElementById`, which is the correct method for accessing elements by their ID.

## Lessons Learned

This example highlights the importance of careful coding and attention to detail. Typos can easily lead to unexpected behavior and make debugging more challenging. Utilizing a good IDE with linting capabilities can help detect these kind of errors early on.