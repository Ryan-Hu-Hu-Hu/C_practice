# Notes for learning C
## Ch2
printf is a function from the standard I/O library (stdio.h)
After finish the coding, use the folloing script to compile and link the C program
C program usually involves 3 steps:
**Preprocessing**: Proprocessor hadles header files begin with # (or known as directives), adds things to the program and makes modifications
**Compiling**: Compiler translate the program into machine instructions (object code)
**Linking**: Linker combines the object code with additional code (library functions like **pritnf**) to yield a complete executable program


```
gcc -o C_program_output_name C_program_name.c 
```