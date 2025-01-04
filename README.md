# CSS Specificity Gotcha: Unexpected Text Color

This repository demonstrates a subtle CSS specificity issue that can lead to unexpected styling results. The problem arises from the interaction between the specificity of different CSS selectors and the cascading order in which styles are applied.

## Problem

The goal is to style paragraph text within a body element to blue using a `p` selector. However, a more specific selector `body p` has a higher specificity and overrides the style set by the simpler `p` selector.

## Solution

The solution involves understanding and using CSS specificity rules correctly.  By carefully considering the specificity of selectors, developers can avoid unintended style conflicts. In this case, ensuring the `p` selector is more specific or adjusting the `body p` selector's styles will resolve the issue.
