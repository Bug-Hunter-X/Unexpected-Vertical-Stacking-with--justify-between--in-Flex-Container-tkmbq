# Unexpected Vertical Stacking with Tailwind's `justify-between`

This repository demonstrates a bug where Tailwind CSS's `justify-between` utility fails to properly distribute space between flex items when one item is significantly larger than the others.  The issue primarily manifests when combined with `flex`, `items-center`, and content size discrepancies.  This results in unexpected vertical stacking rather than the intended horizontal distribution.

The `bug.html` file showcases the issue.  The `solution.html` file provides a potential workaround using `min-width` to ensure a minimum width for the smaller element.