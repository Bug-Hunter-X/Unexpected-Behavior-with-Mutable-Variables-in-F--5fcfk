# Unexpected Behavior with Mutable Variables in F# 

This repository demonstrates a common issue in F# programming involving mutable variables. The code exhibits unexpected behavior due to changes in the values of mutable variables after they have been used in a function. This can be problematic, especially in larger, more complex projects. The solution proposes to improve the code by using immutable variables and functional programming principles.  

## How to reproduce the bug

1. Clone the repository.
2. Open `bug.fs`
3. Run the code.  Observe the output, which might be different than initially expected.

## How to solve the bug

1. Open `bugSolution.fs`
2. Review the code: Notice how the use of immutable variables and functional programming eliminates the unexpected behavior. 
3. Run the code. Observe the consistent and predictable output.