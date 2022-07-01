# Early developments
The origin of C is closely tied to the development of the Unix operating system, originally implemented in assembly language on a PDP-7 by Dennis Ritchie and Ken Thompson, incorporating several ideas from colleagues. Eventually, they decided to port the operating system to a PDP-11. The original PDP-11 version of Unix was also developed in assembly language

# New B and first C release
In 1971, Ritchie started to improve B, to utilise the features of the more-powerful PDP-11. A significant addition was a character type. He called this New B. Thompson started to use NB to write the Unix kernel, and his requirements shaped the direction of the language development. Through to 1972, richer types were added to the NB language: NB had arrays of int and char; but then were added pointers, ability to generate pointers to other types, arrays of all of these, types to be returned from functions. Arrays within expressions became pointers. A new compiler was written, and the language was renamed to C.

The C compiler and some utilities made with it were included in Version 2 Unix, which is also known as Research Unix

# Structures and the Unix kernel re-write
At Version 4 Unix, released in November 1973, the Unix kernel was extensively re-implemented in C. By this time, the C language had acquired some powerful features such as struct types.

The preprocessor was introduced around 1973 at the urging of Alan Snyder and also in recognition of the usefulness of the file-inclusion mechanisms available in BCPL and PL/I. Its original version provided only included files and simple string replacements: #include and #define of parameterless macros. Soon after that, it was extended, mostly by Mike Lesk and then by John Reiser, to incorporate macros with arguments and conditional compilation.

Unix was one of the first operating system kernels implemented in a language other than assembly. Earlier instances include the Multics system (which was written in PL/I) and Master Control Program (MCP) for the Burroughs B5000 (which was written in ALGOL) in 1961. In around 1977, Ritchie and Stephen C. Johnson made further changes to the language to facilitate portability of the Unix operating system. Johnson's Portable C Compiler served as the basis for several implementations of C on new platforms.

# K&R C
In 1978, Brian Kernighan and Dennis Ritchie published the first edition of The C Programming Language. This book, known to C programmers as K&R, served for many years as an informal specification of the language. The version of C that it describes is commonly referred to as "K&R C". As this was released in 1978, it is also referred to as C78. The second edition of the book covers the later ANSI C standard, described below.

## K&R introduced several language features:
* Standard I/O library
* long int data type
* unsigned int data type
etc...

