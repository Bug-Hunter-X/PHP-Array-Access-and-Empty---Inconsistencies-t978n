# PHP Array Access and `empty()` Inconsistencies

This repository demonstrates a common, yet often overlooked, error in PHP related to array access and the use of the `empty()` function.

The problem stems from a combination of PHP's loose typing and the behavior of `empty()` when dealing with array elements that have a value of 0 or an empty string. 

The `bug.php` file showcases the error, while `bugSolution.php` provides a corrected version using `isset()` for existence checks and careful handling of potential 0 values, effectively resolving the issue.