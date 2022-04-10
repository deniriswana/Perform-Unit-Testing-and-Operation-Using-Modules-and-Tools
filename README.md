# Perform Unit Testing and Operation Using Modules and Tools
This repository explain how to perform unit testing with unittest, function and method, how to perform basic operations by using built-in modules and solve complex computing problems by using built-in modules.

## Outline
- Function
- Object oriented programming Class, object and method.
- Function Argument And Parameter
- Txt File (open, Read and Close)
- os.path, os.remove, os.mkdir
- math library
- datetime()
- Random library
- sys module

## Learning Materials
### Functions
- In mathematics, a function is a process that balances between an input (input) and an output (output).
- In Python, apart from relational functions, functions are also a way to organize reusable code.
- By default, Python will position each parameter in the order in which it was registered at the time it was defined, and must be called in that order.
- The return expression statement will make program execution exit the current function, while returning a specified value.

### Object Oriented Programming (OOP)
- Object Oriented Programming (OOP) is a programming paradigm that is oriented to the concepts of class (class) and object (object). This concept is often used in compiling applications into simple and reusable code
#### Class
The definition of a class uses the class syntax as well as the definition of a function that uses the def syntax, then needs to be called (executed) before it can be used and has an effect on the program.
- Object (object: an instance of a class) Instantion of a class, using function notation i.e. with less opening then closing parenthesis, will produce an object
- Then the result of this Instantion is usually stored in a variable with a representative name

#### Object
The object function returns an empty object. You cannot add new properties or methods to this object. This object is the base for all classes, it holds the built-in properties and methods which are default for all classes.

#### Method
A method in English is called a method, is a special function that belongs to an object, namely the result of instantiation of the class.
- In Python, this special function or method as constructor is named init or commonly pronounced as "Double underscore init"
- The first argument of a method in a class is usually given the name self by a naming convention or standard, although you can also use other names. Even in python there is no special meaning about this self syntax, but it is highly recommended to use this conversion so that the python program you create will be more easily understood by other programs
- As you might have guessed, for a method, it is previously passed an object (result of an instance of a class) as its first argument, in this case named self
Method of object(object method)
- In general, a method is a special function that belongs to an object, i.e. the result of an instantiation of a class

#### Def Function
In Python, defining the function works as follows. def is the keyword for defining a function. The function name is followed by parameter(s) in (). The colon : signals the start of the function body, which is marked by indentation. Inside the function body, the return statement determines the value to be returned.

#### Method of Class
- Class Method is a function that converts a method into a method of the class (class method). In its use, this function is used as the @classmethod decorator function, then the call can be directly from the defined class or through the object.
- The method of (class method) accepts input from the class implicitly as the first argument which is conventionally named cls

#### Static Method
- Static Method is a function that converts a method into a static method (static method). In its use, this function is used as a @staticmethod decorater function, then the call can be directly from the defined class or through the object.
- Static Method (static method) does not accept the input of the first argument implicitly

### Function Argumentd and Parameters
Arguments that can be passed to the function As the value to be entered when the function is called, there are 2 types of arguments

1. Keyword Argument
Keyword arguments, namely arguments that are accompanied by an identifier or parameter name that is explicitly mentioned. This includes if we pass values ​​through a dictionary that are preceded by two signs * and (**)

3. Positional Argument
Keyword arguments, namely arguments that are accompanied by an identifier or parameter name that is explicitly mentioned. This includes if we pass values ​​through a dictionary that are preceded by two signs * and (**)

#### Syntax Prefix
syntax prefix * is used as an iterable marker in Python, while prefix ** is used as a container/dictionary marker. Function Parameter Order. There are 5 possible sequences of functions in python:
- Positional or keyword : You can write arguments as keyword arguments or positional arguments
- Positional Only : You specify that certain arguments can only be placed in certain positions. This is done by declaring the main position followed by a / .
- Keyword Only : You specify that certain arguments must be supplied in the form of keyword arguments. This is done by declaring one var-positional argument followed by an *.
- Var-positional and var-keyword : You specify that there are several positional arguments and there are several keyword arguments that you will process. var-positional is marked with a prefix(iterable) and var-keyword is marked with a prefix*(dictionary)
- If there are dynamic positional arguments and dynamic keyword arguments, the order is positional arguments first, then keyword arguments

#### Positional Argument
- Anonymous Function, not declared like other functions with the def keyword, but instead use the lambda keyword
- A lambada function can accept any number of arguments, but returns only one expression value
- Lambda functions cannot load other commands or expressions. for example can not print.
- Lambda functions are self-contained, have their own namespace, and cannot access any values ​​other than those in parameter lists and global variables

### Open, Read and Close
#### open()
- Opening a file refers to getting the file ready either for reading or for writing.
- This function returns a file object and takes two arguments, one that accepts the file name and another that accepts the mode (Access Mode).
- The file should exist in the same directory as the Python script, otherwise, full address of the file should be written.

#### read()
- The read() function reads from an open file.
- As for readlines() returns a list containing each  line in the file as a list item.

#### close()
- It is a standard practice to close an opened file as a closed file reduces the risk of being unwarrantedly modified or read.
- The close() method can be called more than once and if any operation is performed on a closed file it raises a ValueError.

### os and io modules
The OS module in Python provides functions for creating and removing a directory (folder), fetching its contents, changing and identifying the current directory, etc.

As for python io module allows us to manage the file-related input and output operations. The advantage of using the IO module is that the classes and functions available allows us to extend the functionality to enable writing to the Unicode data.

#### os.path()
- The module called os contains functions to get information on local directories, files, processes, and environment variables.
- os.path module is sub module of OS module in Python used for common path name manipulation.
- os.path.isfile() method in Python is used to check whether the specified path is an existing regular file or not.

#### os.remove()
- os.remove() method in Python is used to remove or delete a file path. This method can not remove or delete a directory. 

#### os.mkdir()
- os.mkdir() method in Python is  used for creating or making a new directory. This method raise FileExistsError if the directory to be created already exists.

### math library
math or mathematical function is a module provides access to the mathematical functions defined by the C standard. The math module has many functions which you can learn about here: https://docs.python.org/3/library/math.html 

### datetime()
- A date in Python is not a data type of its own, but we can import a module named datetime to work with dates as date objects.
- When we execute datetime, the date contains year, month, day, hour, minute, second, and microsecond
- The strftime() Method. is a method for formatting date objects into readable strings. The method is called strftime(), and takes one parameter, format, to specify the format of the returned string.
- A reference of all the legal format codes: https://docs.python.org/3/library/datetime.html

### Random Library with radint()
randint() is an inbuilt function of the random module in Python3. The random module gives access to various useful functions and one of them being able to generate random numbers, which is randint().

### sys module
The python sys (System-specific parameters and functions) module provides functions and variables which are used to manipulate different parts of the Python Runtime Environment. It lets us access system-specific parameters and functions.

The sys library has many functions, one of them is sys.exc_info() wich returns an  information about the exception that is currently being handled.  Other functions can be checked here https://docs.python.org/3/library/sys.html






