# Chapter - 02 | Comments
## Overview

- Comments in Python 
- Single-line Comments 
- Multi-line Comments

## Comments in Python

Comments are non-executable statements. It means neither the Python compiler nor the PVM will execute them. Comments are for the purpose of understanding human beings and not for the compiler or PVM. Hence, they are called non-executable statements. There are two types of comments in Python: *single-line comments* and *multi-line comments*.

## Single-line Comments

These comments start with a hash symbol (*`#`*) and are useful to mention that entire line till the end should be treated as comment. For example,

```python
# Program to print "Hello, world!"
print("Hello, world!") # output is Hello, world!
```

Here the first line starts with a `#` and hence the entire line is treated as a comment. In the second line we see `print(“Hello, world!”)` is a statement. After this statement `#` symbol starts the comment describing that the output of this statement is `Hello, world!`. The part of this line starting from `#` symbol to the end is treated as a comment. This type of comments are called *In-line Comments*.

## Multi-line comments

One way of writing multi line comments is to put a hash symbol (`#`) in beginning of every line *for example,*

```python
# This is a comment
# written in
# more than just one line
print("Hello, World!")
```
As you can see that it is a tedious job for appling a `#` symbol every single line. Instead of starting every line with a `#` symbol, we can write the previous block of code inside `"""` (triple double quotes) or `'''` (triple single quote) in the beginning and ending of the block as :
