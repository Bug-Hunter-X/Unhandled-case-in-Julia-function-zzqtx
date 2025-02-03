# Unhandled Case in Julia Function

This repository demonstrates a common error in Julia: a function that doesn't explicitly handle all possible input cases.

The `bug.jl` file contains a function that calculates the square of a number, but fails to handle the case where the input is zero. This can lead to unexpected behavior or errors.

The `bugSolution.jl` file provides a corrected version of the function that addresses this issue using a ternary operator, simplifying the code. 

## How to reproduce the error

1. Save the contents of `bug.jl` as a `.jl` file.
2. Run the file using the Julia REPL or another suitable execution method.
3. Call the `myfunction` with an input of 0.  You will see that the function returns nothing, leading to an error. 

## How to fix the error

The solution provided in `bugSolution.jl` modifies the function to explicitly return a value when the input is 0, handling all possible cases.