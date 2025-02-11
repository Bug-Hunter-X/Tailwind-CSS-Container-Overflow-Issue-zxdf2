# Tailwind CSS Container Overflow Bug

This repository demonstrates a common issue when using Tailwind CSS's `container` utility: content overflowing the container's bounds.  The `bug.html` file shows the problem, while `solution.html` provides a fix.

The problem arises because `container` sets a maximum width, but doesn't inherently prevent content from exceeding that width. This bug is reproduced when the text content within the container is longer than the container's specified width. 

The solution involves using additional Tailwind CSS classes to control the text wrapping and ensure that the content stays within the container's boundaries.