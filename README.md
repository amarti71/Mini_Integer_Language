# Mini_Integer_Language

This project implements a line-by-line integer-based programming language that allows for assignment, operations, and printing using a custom tokenizer and parser.

## Syntax Rules

VALUE (either an integer literal or a variable reference)  
Unless assigning, VALUE must be pre-defined before operating on it.

## Valid Operations
(Spaces don't matter)  
(Operations evaluate left to right)

VALUE + VALUE  
VALUE * VALUE  
VALUE / VALUE  
VALUE - VALUE

## Valid Assignment (may also declare a variable)

VALUE = OPERATION  
You may also define a new variable by typing the name without assignment.

## Valid Print
(In this case, VALUE may be an integer literal, a pre-defined reference, or an operation)

PRINT VALUE

## Example Case

x = 3  
y = x*2  
PRINT y * x + 2  
> 20

y = z + 3  
> SYNTAX ERROR!

## Note

This language also supports negative numbers. Just be sure not to include any spaces between the negative sign and the integer.




