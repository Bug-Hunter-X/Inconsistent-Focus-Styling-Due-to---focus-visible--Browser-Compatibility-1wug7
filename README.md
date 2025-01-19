# Inconsistent Focus Styling Due to `:focus-visible` Browser Compatibility

This repository demonstrates a common issue with the `:focus-visible` pseudo-class in CSS: lack of support in older browsers.  This can lead to inconsistent visual feedback for focused elements, impacting user experience and accessibility.

The `bug.css` file shows the implementation using `:focus-visible`.  The `bugSolution.css` file provides a solution using JavaScript to detect focus and apply appropriate styling across all browsers.