# Unexpected box-shadow expansion in CSS

This repository demonstrates a common yet subtle issue in CSS involving the `box-shadow` property.  The `box-shadow` property, while visually enhancing elements, can unexpectedly expand the element's effective dimensions beyond its declared `width` and `height`. This can lead to layout problems, particularly when elements are positioned or sized relative to each other.

The `bug.css` file shows the problem.  `bugSolution.css` offers a fix to mitigate the issue.