# Tailwind CSS Gradient Bug

This repository demonstrates a common issue encountered when using Tailwind CSS gradients. Specifically, the problem arises from using incompatible color scales or omitting the `to` value in the gradient directive.

The `bug.html` file showcases the problematic code, while `bugSolution.html` provides a corrected version.

## Reproducing the Bug

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the unexpected or missing gradient.

## Solution

The solution involves ensuring that the `from-` and `to-` values are from compatible color scales and both are specified explicitly. Refer to `bugSolution.html` for a corrected implementation.