# CSS Specificity Bug: Unexpected Style Override

This repository demonstrates a common, yet easily overlooked, bug in CSS related to specificity. The issue arises from the unexpected overriding of styles due to the higher specificity of selectors involving ID selectors.

## The Bug
The `bug.css` file contains CSS that demonstrates this problem.  A container element's style is unintentionally overridden by a child element's style because of ID selector specificity. 

## The Solution
The solution is shown in `bugSolution.css`.  It highlights how to correctly manage the cascade using more appropriate selectors, potentially leveraging the `!important` flag (though its use should be carefully considered).