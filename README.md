# Uncommon Julia Bug: Zero Handling in Conditional Statement

This repository demonstrates an uncommon bug in Julia related to the handling of zero values within conditional statements.  The `bug.jl` file contains a function with a subtle error that might not be immediately apparent.

The `bugSolution.jl` provides the solution and improved handling of the edge case.

This example highlights the importance of explicitly considering zero as a potential input value in functions, even if it might seem implicitly handled by the existing conditions.