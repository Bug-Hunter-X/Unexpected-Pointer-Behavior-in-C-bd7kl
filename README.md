# Unexpected Pointer Behavior in C

This repository demonstrates a common, yet subtle, bug related to pointer arithmetic in C. The provided code compiles and runs without errors, but exhibits unintended behavior due to an improper handling of pointers.

## Description
The original code snippet initializes an integer variable and assigns its address to a pointer. Subsequently, the value pointed to by the pointer is modified. The issue lies in the assumption that the memory location pointed to by the pointer remains unchanged. This is not guaranteed in all situations leading to potential memory corruption or unexpected behavior.  The solution demonstrates a more robust and safe approach.