# Mini\_Integer\_Language

this project implements a line by line integer based programming language that allows for assignment, operations, and printing using a custom tokenizer and parser.



\# Syntax rules:



VALUE (either an integer literal or a variable reference)

Unless assigning, Value must be pre-defined before operating on



\## Valid Operations...

(Spaces don't matter)

(Operations evaluate left to right)

VALUE + VALUE

VALUE \* VALUE

VALUE / VALUE

VALUE - VALUE



\## Valid Assignment (may also declare a variable)...

VALUE = OPERATION

(you may also define a new variable by typing the name without assignment)



\## Valid Print...

(in this case, VALUE may be an integer literal, a pre-defined reference or an operation)

PRINT VALUE



\## EXAMPLE CASE...

x = 3 \[ENTER]

y = x\*2 \[ENTER]

PRINT y \* x + 2 \[ENTER]

> 20

y = z + 3 \[ENTER]

> SYNTAX ERROR!



\## Note

This language also allows for the support of negative numbers, just be sure to not include any spaces between the negative sign and the integer







