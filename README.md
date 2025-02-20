# Assembly Infinite Loop Bug

This repository demonstrates a common error in assembly programming: an infinite loop caused by the `jmp $` instruction.  The `jmp $` instruction unconditionally jumps to the current address, resulting in a program that runs indefinitely.

**Bug:**

The `bug.asm` file contains an assembly program with an infinite loop created using `jmp $`. This prevents the program from proceeding to its intended termination point.

**Solution:**

The `bugSolution.asm` file provides a corrected version of the code. The infinite loop is removed, and a proper termination point is established.

This example highlights the importance of careful code design and testing in assembly language programming, where subtle errors can lead to unexpected and hard-to-debug behaviors.