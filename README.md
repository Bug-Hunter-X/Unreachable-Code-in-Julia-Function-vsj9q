# Unreachable Code in Julia Function

This example demonstrates an unreachable code error in a Julia function.  The `return 0` statement is unreachable because the function always returns a value before reaching it due to the prior `if-else` block. This code is technically correct, but it's poor style; the unreachable code should be removed. This is a subtle bug that can be easily overlooked.