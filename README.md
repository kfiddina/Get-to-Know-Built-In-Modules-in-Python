# Get to Know Built-In Modules in Python
## Functions Argument and Parameter
### Argument
An argument is a value that is sent to the function when it is called.<br>
There are 2 types of argument in Python:
* **Keyword Argument**, Keyword Argument means that a function argument has an identifier.
* **Positional Argument**, Positional Argument means that a function argument must be provided in a correct position in a function call.
### Parameter
A parameter is a value listed inside the parentheses in the function definition.<br>
According to Python Documentation, there are 5 kinds of parameters:
* **positional-or-keyword**, specifies an argument that can be passed either positionally or as a keyword argument.
*	**positional-only**, specifies an argument that can be supplied only by position.
*	**keyword-only**, specifies an argument that can be supplied only by keyword.
*	**var-positional**, specifies that an arbitrary sequence of positional arguments can be provided.
*	**var-keyword**, specifies that arbitrarily many keyword arguments can be provided.

## Object-Oriented Programming 
Object-Oriented Programming (OOP) is a programming paradigm based on the concept of "objects". An object-oriented paradigm is to design the program using classes and objects.

## Working with txt File 
*	**Open**, To open the file using the built-in open() function. The open() function returns a file object, which has a read() method for reading the content of the file.
*	**Read**, read() method returns the whole text, but you can also specify how many characters you want to return.
*	**Close**, It is a good practice to always close the file when you are done with it. To close file using close() function.
*	**Delete**,  To delete a file, you must import the OS module, and run its os. remove() function.

## Operating Using Modules and Tools
*	**IO**, io Module can be used to create .txt files without uploading files to google collaboratory.
*	**OS**, os.path Module here is used to create a new file if it is not available, but if it already exists, it will add text only.
*	**Pydoc**, There is a python module built-in that can be used to check the presence of a particular python module on our device. To be able to run pydoc can not be done in google colab or jupyter notebook but in the command prompt.
*	**Unit Test**, The Python standard library includes the unit test module to help write and run tests for your Python code. Tests are written using the unit test module help to find bugs in the programs, and prevent regressions from occurring when code change over time.
*	**Math**, This module provides access to the mathematical functions defined by the C standard.
*	**Date Time**, The datetime module supplies classes for manipulating dates and times. While date and time arithmetic is supported, the focus of the implementation is on efficient attribute extraction for output formatting and manipulation.
*	**Random**, This module implements pseudo-random number generators for various distributions.
*	**Sys**, The sys module in Python provides various functions and variables that are used to manipulate different parts of the Python runtime environment.
