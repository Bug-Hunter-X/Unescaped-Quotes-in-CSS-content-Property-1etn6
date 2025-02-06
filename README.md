# Unescaped Quotes in CSS `content` Property

This repository demonstrates a common but easily overlooked error in CSS: unescaped quotes within the `content` property used with `::before` or `::after` pseudo-elements.

Unescaped quotes can lead to unexpected rendering issues because the CSS parser might prematurely terminate the string, resulting in incomplete or incorrect content.

**bug.css** shows the problematic code.  **bugSolution.css** demonstrates the correct way to escape quotes for proper rendering.

This issue is particularly relevant when dynamically generating content or working with user inputs that might contain quotes.