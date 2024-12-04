# Lua Implicit Type Conversion Bug

This repository demonstrates a common error in Lua programming related to implicit type conversion.  Lua's flexibility in type handling can sometimes cause unexpected behavior, particularly when performing arithmetic operations on values of different types.

The `bug.lua` file contains code that attempts to add a number to a string, resulting in a runtime error.  The `bugSolution.lua` file provides a corrected version with explicit type checking to prevent this error.