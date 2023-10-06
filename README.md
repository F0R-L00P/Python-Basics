# Python-Basics
introduction to basic components and building blocks of what makes python AWESOME!

## Python Manual
https://docs.python.org/3/tutorial/index.html

## Python Tutor
https://mail.python.org/mailman/listinfo/tutor

## Online Python Interpreter
https://www.python.org/shell/

## Cheat Sheets
Arithmetic operators  
Python can calculate numbers using common mathematical operators:  

| Expression | Description                                                                                     |
|------------|-------------------------------------------------------------------------------------------------|
| `x + y`    | Addition `+` operator returns the sum of x plus y                                               |
| `x - y`    | Subtraction `-` operator returns the difference of x minus y                                     |
| `x * y`    | Multiplication `*` operator returns the product of x times y                                     |
| `x / y`    | Division `/` operator returns the quotient of x divided by y                                     |
| `x**e`     | Exponent `**` operator returns the result of raising x to the power of e                        |
| `x**2`     | Square expression returns x squared                                                             |
| `x**3`     | Cube expression returns x cubed                                                                 |
| `x**(1/2)` | Square root (½) or (0.5) fractional exponent operator returns the square root of x               |
| `x // y`   | Floor division `//` operator returns the integer part of the integer division of x by y          |
| `x % y`    | Modulo `%` operator returns the remainder part of the integer division of x by y                 |

## Order of operations
The order of operations are to be calculated from left to right in the following order:  

**B**rackets ( ), { }, [ ]

**E**xponents x<sup>e</sup> (`x**e`)

**D**ivision / and **M**ultiplication *

**A**ddition + and **S**ubtraction -    

 You might find the **BEDMAS** mnemonic device to be helpful in remembering the order.   

## More Resources  

[Built-in Functions](https://docs.python.org/3/library/functions.html) - Lists and summarizes Python’s built-in functions.  

[Python Keywords](https://www.w3schools.com/python/python_ref_keywords.asp) - Lists Python’s reserved keywords and a brief description of what each keyword does.  

[Different Arithmetic operators in Python](https://flexiple.com/python/arithmetic-operators-in-python) - Provides more examples of the proper syntax for using arithmetic operators in Python.

---
## Data Types
In Python, text in between quotes is a string data type. An integer is a whole number, while a float is a real number that can contain a fractional part. When attempting to mix incompatible data types, you may encounter a TypeError. You can always check the data type of something using the **type()** function.

## Implicit vs Explicit Conversion
Some data types can be mixed and matched due to implicit conversion. For example, adding int with float. Implicit conversion is where the interpreter helps us out and automatically converts one data type into another, without having to explicitly tell it to do so.

Explicit conversion is where we manually convert from one data type to another by calling the relevant function for the data type we want to convert to. For example, when we wanted to print a number alongside some text. Before we could do that, we needed to call the str() function to convert the number into a string. Once the number was explicitly converted to a string, we could join it with the rest of our textual string and print the result.

```python
number = 2
print("I have " + str(number) + "apples")
"I have 2 apples"


