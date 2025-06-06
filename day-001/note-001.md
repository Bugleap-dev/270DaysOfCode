# **DAY 001 - 15/04/2025**

# **CS50P: Introduction To Programming with Python**
    
# **LECTURE 0: Function_Variable**

## Table of Contents
1. [Definition](#Definition)
2. [Parameters](##Parameters)
3. [Difference between Arguments and Parameters](#differnce-between-arguments-and-parameters)
4. [Differnce between using Comma and plus for Concatenation](#differnce-between-using-comma-and-plus--for-concatenation)

---
# Definition
- **$code hello.py**: Creates a file "hello" in python(py) format

- **Syntax**: refers to the sedof rules that defines hoe code must be written for the computer to understand it, i.e Syntax = the rules for writing code correctly.

- **$python hello.py**: runs the python code "hello.py"

- **Function** : is an action or a verb that lets you do something in the program.

- **Arguments**: is an input to a function that influences its behaviour.

- **Side Effects**: is the display of a function, it could be visual, audio, etc.

- **Bugs**: is a mistake in a program.

- **Return values**: is the result that a function gives back after execution.

- **Variable**: is a placeholder for information you want python to recall later in the coding process when you need to complete an action.

- **Comments**: are notes in a code, it is written with an **Hash(#)** at the beginning or three quotation marks at the beginning and end for multiple lines (" " ").

- **Pseudo-code**: is plain English, half code outline describing a program's logic, serving as a blueprint before writing actual code, using the **Hash (#)** for comments.

## **Parameters**
- Parameters: are variables used in function definitions to accept input values when the function is called.

- * Name parameter: parameters that must be passed in the correct order.
- * Position parameter: parameters with default values, used if no argument is provided.

### ***DIFFERNCE BETWEEN ARGUMENTS AND PARAMETERS***
   * Parameters acts a placeholder for the values that will be passed.
   * While Arguments are actual values passed to the function when you call it.

- **Concatenation**: the process of joining two or more string into a new string. This is done using operators the ***plus operator (+).***

### ***DIFFERNCE BETWEEN USING COMMA(,) AND PLUS (+) FOR CONCATENATION***
   * Using + (Concatenation Operator): joins strings together with no space. Both operands must be string.
   * Using , (concatenation operator): Automatically adds a space between items. Can mix data types(e.g string and int without conversion).

**FROM PYTHON DOCUMENATION:**
- *docs.python.org/3/library/functions.html*
    - Print() Syntax: 
    ```python
    print(*objects,sep=' ',end='\n',file=sys.stdout,flush=False)
    ```

 - * *objects : the values to be printed. Can be multiple items.
    - * sep='' : seperator between the objects(default is a space).
    - * end=\n : what to print at the end(default is newline).

- **\n** is the *newline character*. It tells the program to move the cursor to the next line when printing text. *\n* = "linebreak"

- * **USING QUOTATION MARKS INSIDE PRINT() FUNCTION**
    - * Using Escape character(\n)
    - * Using Different quotation mark, single quotation(''), double quotation, (""), triple quoatation("' '")

- **F-string**: is a way to make strings that include variables or expressions directly inside them by putting an **f** before the string and using {} to insert values.
