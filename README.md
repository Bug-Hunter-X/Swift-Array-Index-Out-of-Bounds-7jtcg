# Swift Array Index Out of Bounds

This repository demonstrates a common error in Swift programming: the array index out of bounds error.  The error occurs when you attempt to access an element of an array using an index that's either negative or greater than or equal to the array's count.

The `bug.swift` file contains code that reproduces this error. The `bugSolution.swift` file provides a solution that checks the index for validity before accessing the element, preventing the crash.