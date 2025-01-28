# Responsive Navigation Bar Issue with Flexbox

This repository demonstrates a common issue encountered when using flexbox for responsive layouts. The navigation bar elements are intended to distribute evenly across the screen, but they stack vertically instead. The `bug.css` file contains the faulty CSS code, while `bugSolution.css` provides the corrected version.

## Problem

The provided CSS code uses flexbox to create a responsive navigation bar. However, the navigation bar items stack vertically instead of distributing evenly across the available width. This occurs because the default flex-basis isn't always handled correctly, especially when items have varying content lengths.