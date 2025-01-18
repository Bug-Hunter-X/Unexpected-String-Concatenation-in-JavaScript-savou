# Unexpected String Concatenation in JavaScript

This repository demonstrates a common JavaScript bug related to type coercion and the `+` operator.  The code in `bug.js` showcases how adding a number and a string using the `+` operator results in string concatenation rather than numerical addition.  The `bugSolution.js` file presents a solution to avoid this unexpected behavior. 

**Bug:** The `foo` function intends to perform numerical addition. However, due to type coercion, it performs string concatenation when passed a number and a string. 

**Solution:** Explicit type conversion is used to ensure numerical addition.