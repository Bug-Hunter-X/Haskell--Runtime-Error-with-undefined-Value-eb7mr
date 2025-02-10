# Haskell: Runtime Error with undefined Value

This repository demonstrates a common runtime error in Haskell caused by using the `undefined` value.  The `bug.hs` file contains the erroneous code. The `bugSolution.hs` file provides a corrected version.

**Problem:**
The program attempts to perform arithmetic operations on an undefined value, leading to a runtime error. This commonly arises from incomplete pattern matching in functions or forgetting to define a value before usage.

**Solution:**
The solution involves ensuring that all possible cases in a function are handled and that values are defined before being used in computations.  In more complex scenarios, using the `Maybe` or `Either` type to handle potential errors might be necessary.