# Structures
A structure, is basically a collection of elements of ***Same/Different*** data types. <br />
More formally, A struct in the C programming language (and many derivatives) is a composite data type declaration that defines a physically grouped list of variables to be placed under one name in a block of memory, allowing the different variables to be accessed via a single pointer, or the struct declared name which returns the same address. 
## Why structures over array?
An array is a collection of elements of same data type. Using an array to solve real world problems is not logical as the data that the user may want to store can contain elements of many different data types, such as integer, float, character, string.... and the list goes on. <br />
Therefore,<b> using structures over array is a more logical choice as it provides more flexibility to store more diverse data in a single functional unit </b>
## Declaration
The general syntax for a struct declaration in C is: <br />
```
    struct tag_name {
        type member1;
        type member2;
        /* declare as many members as desired, but the entire structure size must be known to the compiler. */
    };
```
Using structures is the first step we take to store and solve real world problems using code.

### Index
  1. [Example of using structure in C language](struct.c)