# Go Array Index Out of Bounds Bug

This repository demonstrates a common error in Go: accessing an array index that is out of bounds.  The code attempts to assign values to an array of size 5, but the loop iterates from 0 to 5 (inclusive), resulting in an index out of bounds error (panic).

The solution shows how to fix the error by adjusting the loop condition to correctly iterate within the bounds of the array.