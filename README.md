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
```
## Functions
A reference guide for functions

**return value** - the value or variable returned as the end result of a function

**parameter (argument)** -  a value passed into a function for use within the function

**refactoring code** - a process to restructure code without changing functionality

The purpose of the **def()** keyword is to define a new function. Best practices for writing code that is readable and reusable:

**Create a reusable function** - Replace duplicate code with one reusable function to make the code easier to read and repurpose.

**Refactor code** - Update code so that it is self-documenting and the intent of the code is clear.

**Add comments** - Adding comments is part of creating self-documenting code. Using comments allows you to leave notes to yourself and/or other programmers to make the purpose of the code clear.

## Comparison Operators with Equations
The following examples demonstrate how to use comparison operators with the data types int and float. Comparison operators return Boolean results. 

Boolean is a data type that can hold only one of two values: `True` or `False`.  

The comparison operators include: 

- `==` (equality)
- `!=` (not equal to)
- `>` (greater than)
- `<` (less than)
- `>=` (greater than or equal to)
- `<=` (less than or equal to)
 

## PART 1: Equality == and Not Equal To != Operators
In Python, you can use comparison operators to compare values. When a comparison is made, Python returns a Boolean result: **True** or **False**. Note that Boolean data types are not string data types (Boolean True is not equal to the string "True").  

To check if two values are the same, use the **equality operator: ==**

To check if two values are not the same, use the **not equal to operator: !=**

```python
print(32 == 30+2)   # The == operator checks if the 2 values are 
True                # equal to each other. If they are equal, 
                    # Python returns a True result.


print(5+10 == 6+7)  # If the two values are not equal, as in the
False               # expression 5+10 == 6+7 (or 15 == 13), Python          
                    # returns a False result.


print(10-4 != 10+4) # The != operator checks if the 2 values are
True                # NOT equal to each other. If true, Python              
                    # returns a True result. 



print(9/3 != 3*1)   # In this last example, 9/3 != 3*1 (or 3 != 3)
False               # is false. So, Python returns a False value.
```
## PART 2: Greater Than > and Less Than < Operators
The comparison operators greater than `>` and less than `<` also return a `True` or `False` Boolean result after comparing two values.

To check if one value is larger than another value, use the greater than operator: `>` 

To check if one value is smaller than another value, use the less than operator: `<` 
```python
print(11 > 3*3)         # The > operator checks if the left value is
True                    # greater than the right value. If true, it
                        # returns a True result.
```
## PART 3: Greater Than or Equal to >= and Less Than or Equal to <= Operators
Like the other comparison operators, the greater than or equal to `>=` and less than or equal to `<=` operators return a `True` or `False` Boolean result when a comparison is made.

To check if one value is larger than or equal to another value, use the greater than or equal to operator: `>=` 

To check if one value is smaller than or equal to another value, use the less than or equal to operator: `<=` 
```python
print(12*2 >= 24)   # The >= operator checks if the left value is
True                # greater than or equal to the right value. 
                    # If one of these conditions is true,  
                    # Python returns a True result. In this case  
                    # the two values are equal. So, the comparison
                    # returns a True result.
```
## Key Takeaways

Python comparison operators return Boolean results: `True` or `False`.

| Symbol | Name                               | Expression | Description                        |
|--------|------------------------------------|------------|------------------------------------|
| `==`   | Equality operator                  | `a == b`   | `a` is equal to `b`                |
| `!=`   | Not equal to operator              | `a != b`   | `a` is not equal to `b`            |
| `>`    | Greater than operator              | `a > b`    | `a` is larger than `b`             |
| `>=`   | Greater than or equal to operator  | `a >= b`   | `a` is larger than or equal to `b` |
| `<`    | Less than operator                 | `a < b`    | `a` is smaller than `b`            |
| `<=`   | Less than or equal to operator     | `a <= b`   | `a` is smaller than or equal to `b`|
