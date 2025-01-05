# Haskell Sort Function Unexpected Behavior

This repository demonstrates an unexpected behavior of the `sort` function in Haskell.  The `sort` function in Data.List returns a *new* sorted list, rather than modifying the original list in place. This can lead to unexpected results if you're not aware of this behavior.

The `bug.hs` file contains code illustrating this issue.  The `bugSolution.hs` file demonstrates the correct approach, which is to assign the result of `sort` to a new variable.

This demonstrates a common misunderstanding of Haskell's pure functional nature.