# CSS Specificity Bug: Unexpected Style Conflicts

This repository demonstrates a common CSS issue related to selector specificity.  The bug involves unexpected style conflicts arising from the cascading nature of CSS and the order of stylesheets or the specificity of selectors themselves. The solution highlights how to correctly identify and resolve these conflicts.

## Bug Description

The core problem lies in understanding how the browser resolves conflicting CSS styles. The order of CSS rules does not always determine which style is applied. The specificity of selectors plays a crucial role.  This bug manifests as unexpected visual styles that deviate from what was intended.

## Solution

The solution clarifies selector specificity (ID > Class > Element) and how to approach the CSS cascade to create the desired visual outcome. Using browser developer tools to inspect the computed styles helps diagnose such issues.