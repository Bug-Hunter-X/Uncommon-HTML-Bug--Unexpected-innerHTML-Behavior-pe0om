# Uncommon HTML Bug: Unexpected innerHTML Behavior

This repository demonstrates an uncommon bug related to the use of `innerHTML` in HTML.  Repeatedly appending to `innerHTML` can lead to performance issues and unexpected rendering behavior.  The solution shows a more efficient and reliable approach.

## Bug Description

The `bug.html` file shows an example where appending to `innerHTML` within a loop or repeatedly may cause issues. This could manifest as unexpected rendering or significantly slower performance.  It's a subtle issue that's easily overlooked.

## Solution

The `bugSolution.html` file demonstrates how to use `insertAdjacentHTML` for better performance and reliability when adding content to the DOM.