# Unhandled IllegalArgumentException in Scala Setter Method

This repository demonstrates a common error in Scala: an unhandled `IllegalArgumentException` thrown within a setter method.  The `bug.scala` file shows the problematic code, while `bugSolution.scala` provides a corrected version.

**Problem:** The original code throws an `IllegalArgumentException` if a negative value is assigned to the `value` property of the `MyClass` object.  However, the exception is not caught, leading to program termination.

**Solution:** The corrected code uses a `try-catch` block to handle the exception gracefully.  This prevents the program from crashing and allows for more robust error handling.