# 0x06. C - More pointers, arrays and strings

## Pointers
A pointer is a variable which contains a memory address.

Pointers in C are easy and fun to learn. Some C programming tasks are performed more easily with pointers, and other tasks, such as dynamic memory allocation, cannot be performed without using pointers. So it becomes necessary to learn pointers to become a perfect C programmer.

## Arrays
Arrays in C are contiguous memory areas that hold a number of values of the same type. Unlike some other languages, in C, all elements of an array have the same type. Arrays a kind of data structure that can store a fixed-size sequential collection of elements of the same type. An array is used to store a collection of data, but it is often more useful to think of an array as a collection of variables of the same type.

## Strings
Strings are actually one-dimensional array of characters terminated by a null character '\0'. Thus a null-terminated string contains the characters that comprise the string followed by a null.

## Memory Layout
Basically, the memory layout of C program contains five segments these are the stack segment, heap segment, BSS (block started by symbol), DS (Data Segment) and text segment. Each segment has own read, write and executable permission. If a program tries to access the memory in a way that is not allowed then segmentation fault occurs.

A segmentation fault is a common problem that causes programs to crash. A core file (core dumped file) also associated with a segmentation fault that is used by the developer to finding the root cause of the crashing (segmentation fault).
