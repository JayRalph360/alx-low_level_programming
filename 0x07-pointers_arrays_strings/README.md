# C - Pointer to Pointer

A pointer to a pointer is a form of multiple indirection, or a chain of pointers. Normally, a pointer contains the address of a variable. When we define a pointer to a pointer, the first pointer contains the address of the second pointer, which points to the location that contains the actual value.

A variable that is a pointer to a pointer must be declared as such. This is done by placing an additional asterisk in front of its name. For example, the following declaration declares a pointer to a pointer of type int.

## C – Pointer to Pointer (Double Pointer) with example

We already know that a pointer holds the address of another variable of same type. When a pointer holds the address of another pointer then such type of pointer is known as pointer-to-pointer or double pointer. In this guide, we will learn what is a double pointer, how to declare them and how to use them in C programming. To understand this concept, you should know the basics of pointers.

# Multi-dimensional Arrays in C

C programming language allows multidimensional arrays. Here is the general form of a multidimensional array declaration −
type name[size1][size2]...[sizeN];
For example, the following declaration creates a three dimensional integer array −
int threedim[5][10][4];

## Two dimensional (2D) arrays in C programming with example

An array of arrays is known as 2D array. The two dimensional (2D) array in C programming is also known as matrix. A matrix can be represented as a table of rows and columns. Before we discuss more about two Dimensional array lets have a look at the following C program.
