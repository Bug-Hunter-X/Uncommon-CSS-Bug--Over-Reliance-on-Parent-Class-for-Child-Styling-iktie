# Uncommon CSS Bug: Over-Reliance on Parent Class for Child Styling
This repository demonstrates a less common but problematic pattern in CSS where child elements are styled based on their parent's class. This approach can lead to several issues: 

* **Reduced Reusability**: Styles for `.child-class` are tightly coupled to the `.parent-class`, making it difficult to reuse those styles independently.
* **Increased Maintenance**: As the CSS grows, tracking the parent-child relationship for styling becomes challenging and prone to errors. 
* **Debugging Complexity**:  Troubleshooting styling issues becomes more complex since the style of the child depends on its parent's class.

The `bug.css` file showcases the problematic pattern, while `bugSolution.css` illustrates a more maintainable and reusable alternative. 