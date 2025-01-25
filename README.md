# Julia Exponentiation Bug

This repository demonstrates a potential issue when using the exponentiation operator (`^`) in Julia with negative numbers and non-integer exponents. The function `myfunction` calculates the square of a number if it's positive and returns 0 otherwise. However, when using negative inputs, the `^` operator might return unexpected complex numbers, leading to potential problems if the code expects only real numbers.

The `bug.jl` file contains the original code, while `bugSolution.jl` shows a corrected version that uses a more robust approach to handle this case.  This is useful for anyone working with numeric computations in Julia and needs to carefully handle the potential for complex number results.