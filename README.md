Printf
Our first collaborative project at Holberton School, The printf project is a Low-Level Programming project writen in C language.

Table of Context
Files
change log
0.0.1 - 2018-19-10
Authors
Files
Goto	Files	Description
📌	printf.c	Entry point for the printf.
holberton.h	Header files for the the whole project.
global_definitions.h	Header file that defines macro for NULL, True, and False.
📌	opid.c	Contains the functions for handling the function pointers.
📌	buffer_int.c	Contains function to Allocate and free a Buffer.
📌	buffer_ops.c	Contains functions related to the buffer.
📌	buffer_ops2.c	Contains functions related to the buffer.
📌	write_op_funcs.c	Contains functions related to writing out the Buffer to STDOUT.
📌	write_op2_funcs.c	Contains a function that converts binary into base 10 number.
Printf
file: printf.c

Function	Details
_printf	prints any string with certain flags for modification
back to files

opid.c
file: opid.c

Function	Details
opid	opid - scans src string for an operator.
back to files

buffer_int.c
file: buffer_int.c

Function	Details
buf_new	Function that create a Buffer struct at a default size of 1024
buf_custom	Function for create a Buffer struct with a custom size
buf_end	frees buffer structure
back to files

buffer_ops.c
file: buffer_ops.c

Function	Details
buf_size	get the size
buf_index	gets the current index of
buf_content	creates a copy of the buffer str field
buf_write	writes out the buffer string to stdout
buf_wr	writes and reset the buffer string
back to files

buffer_ops2.c
file: buffer_ops2.c

Function	Details
buf_inc	increment both index and overflow.
back to files

write_op_funcs.c
file: write_op_funcs.c

Function	Details
write_char	write a character to buffer
write_str	writes a string to buffer
write_mod	write a modulus symbol
write_int	write integer to the buffer
append_num	Appends a number as an integer to the buffer
back to files

write_op2_funcs.c
file: write_op2_funcs.c

Function	Details
write_bin	convert a digit to binary.
back to files

change log
0.0.1 - 2018-19-10
add Martin Branch
Git flow initialized to this project.