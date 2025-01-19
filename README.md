# CSS calc() Unexpected Behavior in Media Queries

This repository demonstrates a problem where the `calc()` function in CSS produces unexpected results when used with percentages within media queries.  The expected behavior is not occurring, resulting in incorrect layout or styling.

## Problem Description

When using `calc()` with percentages inside a media query to calculate widths or other properties, the calculation may not be performed correctly. The value produced may differ from the expected mathematical result.

## Solution

The solution involves modifying the CSS to use a different approach to achieve the desired layout or styling, avoiding the problematic use of `calc()` with percentages within media queries. This could involve using different units (e.g., pixels) or restructuring the CSS layout.

## Setup

1. Clone the repository.
2. Open `bug.css` to see the problematic code and `bugSolution.css` for the solution. 
3. Open the files in a browser and observe the rendered result. 