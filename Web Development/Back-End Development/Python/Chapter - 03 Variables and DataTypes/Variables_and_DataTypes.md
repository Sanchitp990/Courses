# Chapter - 03 | Variables and DataTypes
## Overview

- Data Types in Python 
- Built-in data types
- Variables in Python

## Data Types in Python 

A datatype represents the type of data stored in a variable or memory. The datatypes which can be created by the programmers are called *User-defined* datatypes. 

## Built-in datatypes 

The datatypes which are already in Python language are called *Built-in* datatypes. The built-in datatypes are of five types:

- NoneType 
- Numeric Types
- Boolean Type
- Sequences 
- Sets 
- Mappings

### NoneType 

In Python, the ‘*NonType*’ datatype represents an object that does not contain any value. In Python, we store ‘None’ to represent an empty object and its datatype is considered as ‘*NoneType*’. 

### Numeric Types 

The numeric types represent numbers. There are three sub types: 

- int

    > The int datatype represents an integer number. An integer number is a number without any decimal point number. For example, `200`, `-200`, `0`, `9888998700`, etc., are treated as integer number.

- float

  > The float datatype represents an floating-point number. An floating-point number is a number that contains a decimal point. For example, `0.5`, `-5.3040`, `200.400`, `0.001`, etc., are treated as floating-point number.

- complex 
    > The complex number is a number that is written in the form of a+bj or a+bJ. Here 'a' represents the real part of the number and 'b' represents in imaginary part of the number. The suffix ‘j’ or ‘J’ after ‘b’ indicates the square root value of –1. The parts ‘a’ and ‘b’ may contain integers or floats. For example, 3+5j, -1-5.5J, 0.2+10.5J, etc., are all complex number.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Representing Binary, Octal and Hexadecimal Numbers***

<ins>***Binary Numbers: -***</ins>

A binary number should be written by prefixing 0b (zero and b) or 0B (zero and B) before the value. For example, 0b101010011, 0B101001010, etc., are treated as binary numbers. 

<ins>***Hexadecimal Numbers: -***</ins>

Hexadecimal number are written by prefixing ox (zero and x) or 0X (zero and big X) before the value. For example, 0xA180 or 0X11fb91, etc., are treated as hexadecimal numbers. 

<ins>***Octal Numbers: -***</ins>

Octal numbers are indicated by prefixing 0o (zero and small o) or 0O (zero and then O) before the actual value. For example, 0o773 or 0O145 are octal values. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;***Converting the Datatypes Explicitly***

Python internally assumes the datatype for the variable. But sometimes, the programmer wants to convert one datatype into another type on his own. This is called type conversion or coercion. This is possible by mentioning the datatype with parentheses.

- For example, to convert a number into integer type, we can write.

```python
x = 15.56
int(x) # Output is 15
```

- For example, to convert a number into float type, we can write.

```python
x = 15
float(x) # Output is 15.0
```

- For example, to convert a number into complex type, we can write.

```python
x = 10
complex(x) # Output is 10+0j
```

**Note: -** ***In <ins>complex(x)</ins> is used to convert <ins>‘x’</ins> into a complex number with real part
and imaginary part zero. If you want to replace the imaginary part by other
numbers you can use <ins>complex(x, y)</ins> instead, where <ins>‘x’</ins> represent the real part and <ins>‘y’</ins>
represent the imaginary part. For example,***

```python
x = 10
y = -5
complex(x, y) # Output is 10-5j
```
### Boolean Type
Boolean datatype in Python represents boolean values which is `True` or `False`.
Python internally represents True as `1` and False as `0`. For example,
- let's take a variable `x` value as `5` and variable `y` value as `10`, if `x is Less than y`.

```python
x = 5
y = 10
print(x > y) # Output is True
```

### Sequences 

### Sets 

### Mappings 

## Variables in Python

In Python our even every programming language the defination of variables is almost same which is : "*A variable reffers as a continars whichstore some values or data on it*"

<ins>***OR***</ins>

In 

"*A variable is a name given by a programmer that holds a value or data*". For example.

```python
x = 10 # A variable name x which contains value of 10
```

## Rules to 

In python there are some rules we must need to follow while creating a variable which are listed below:

- Variable names can contain only letters, numbers, and underscores. They can start with a letter or underscore, but not with a number.