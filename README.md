# CSS :nth-child Unexpected Behavior with Negative Indices

This repository demonstrates an uncommon bug related to the use of negative indices within the CSS `:nth-child` selector.  While `:nth-child` is generally straightforward, using formulas that result in negative indices can lead to unexpected and inconsistent behavior across different browsers.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` provides a corrected approach to achieve the intended styling.

This issue highlights the importance of thoroughly testing CSS selectors, particularly those involving complex formulas or negative values, to ensure consistent and predictable behavior across different browsers and environments.