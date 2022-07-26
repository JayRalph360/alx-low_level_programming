# C static libraries

## What is a library
A library is a collection of code routines (functions, classes, variables, and so on) that can be called upon when building our program, so instead of writing it ourselves, we can go and get it from something that has already been written and optimized. That is where the idea behind libraries comes from. 

## What is static library
A static library is a file containing a collection of object files (*.o) that are linked into the program during the linking phase of compilation and are not relevant during runtime.
When a program is compiled, the compiler generates an object file from a source file. After generating the object file, the compiler also invokes the Linker. The role of the linker, in this case, is to copy the code of the library to our object file.
Basically, static libraries are just a collection of object files that are merged by the linker with another object file to form a final executable.
Conventionally, they start with “lib” and end with “.a” or “.lib” (depending on your platform).
