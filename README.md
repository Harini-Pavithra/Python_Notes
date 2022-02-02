# Python Notes

### Introduction
- Python is a programming language that lets you work more quickly and integrate your systems more effectively.
–	Python is an easy to learn,
–	very clear, readable syntax
–	exception-based error handling
–	very high level dynamic data types
- It has efficient high-level data structures and a simple but effective approach to object-oriented programming.
- Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.
- Python can be integrated with another language.
- Python runs everywhere.
- It can be downloaded from http://www.python.org/download

### Arithmetic Operators
- Arithmetic operators are used to perform mathematical operations.
- There are 7 arithmetic operators in Python :
  - Addition - It is used to add 2 values('+')
  - Subtraction - It is used to subtract the second value from the first value('-')
  - Multiplication - It is used to find the product of 2 values('*')
  - Division - It is used to find the quotient when first operand is divided by the second('/')
  - Modulus - It is used to find the remainder when first operand is divided by the second('%')
  - Exponentiation - It is used to raise the first operand to power of second('**')
  - Floor division - It is used to raise the first operand to power of second('//')

### Comparison Operators
- Comparison Operators are used for comparing the values. It either returns True or False according to the condition. These operators are also known as Relational operators.

![Comparison_Operators](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Comparison_Operators.PNG)

### Bitwise Operators
-  Bitwise operators are used to performing bitwise calculations on integers. The integers are first converted into binary and then operations are performed on bit by bit, hence the name bitwise operators

![Bitwise_Operator](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Bitwise_Operator.PNG)

### Assigment Operators
- Assignment Operators are used to assigning values to variables. 

![Assignment_Operators](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Assignment_Operators.PNG)

### Logical Operators
- In Python, Logical operators are used on conditional statements (either True or False). They perform Logical AND, Logical OR and Logical NOT operations.

![Logical_Operators](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Logical_Operators.PNG)

### Membership Operators
- Membership operators are used to test if a sequence is presented in an object:

![Membership_Opeartors](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Membership_Opeartors.PNG)

### Operators Precedence

- The following table lists all operators from highest precedence to lowest.

![Opeartors_Precedence](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Opeartors_Precedence.PNG)

### Data types
- Data types are the classification or categorization of data items.
- Following are the standard or built-in data type of Python:
  - Numeric: numeric data type represent the data which has numeric value.
    - Integer : This value is represented by int class. It contains positive or negative whole numbers (without fraction or decimal). In Python there is no limit to how long an integer value can be.
    - Float: This value is represented by float class. It is a real number with floating point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation.
    - Complex Numbers: Complex number is represented by complex class. It is specified as (real part) + (imaginary part)j. For example – 2+3j.
  - Sequence Type: Sequence is the ordered collection of similar or different data types. Sequences allows to store multiple values in an organized and efficient fashion. 
    - String
    - List
    - Tuple
  - Boolean : Data type with one of the two built-in values, True or False
  - Set
  - Dictionary

### Type Hierarchies

![Type_Hierarchies](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/Type_Hierarchies.PNG)

### Strings in Python
- Strings in python are surrounded by either single quotation marks, or double quotation marks.
```
'hello' is the same as "hello".
```

- The string functions of python are 

### if statement
- The if statement is used to the conditions.
- The elif keyword is pythons way of saying "if the previous conditions were not true, then try this condition".
- The else keyword catches anything which isn't caught by the preceding conditions.
- We can have if statements inside if statements, this is called nested if statements.

Syntax:
```
if condition: statements
[elif condition: statements] ...
else:
statements
```

### for loop
- A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
- This is less like the for keyword in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.
- With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.

Syntax:
```
for var in sequence: 
  statements
``` 

### while loop
- With the while loop we can execute a set of statements as long as a condition is true.

Syntax:
```
while condition: 
  statements
```
### Break, Continue and Pass statements
- The break statement, like in C, breaks out of the smallest enclosing for or while loop.
- The continue statement, also borrowed from C, continues with the next iteration of the loop
- The pass statement does nothing. It can be used when a statement is required syntactically but the program requires no action.

### Strings
- Strings are amongst the most popular types in Python.
- We can create them simply by enclosing characters in quotes.
- Python treats single quotes the same as double quotes.

### String Functions

![String_Functions](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/String_Functions.PNG)

### String Formatting Operators

![String_Formatting_Operators](https://github.com/Harini-Pavithra/Python_Notes/blob/main/images/String_Formatting_Operators.PNG)

### Python Lists:

- The list is a most versatile data type available in Python which can be written as a list of comma-separated values (items) between square brackets.

- Good thing about a list is that items in a list need not all have the same type.

Example:
```
list1 = ['physics', 'chemistry', 1997, 2000]
list2 = [1, 2, 3, 4, 5 ]
list3 = ["a", "b", "c", "d"]
```

### List Operations

1. list.extend(L): Extend the list by appending all the items in the given list.
2. list.append(x):	Add an item to the end of the list.
3. list.remove(x): Remove the first item from the list whose value is x. It is an error if there is no such item.
4. list.clear(): Remove all items from the list. Equivalent to del a[:]
5. list.index(x) : Return the index in the list of the first item whose value is x. It is an error if there is no such item.
6. list.count(x) : Return the number of times x appears in the list.
7. list.reverse(): Reverse the elements of the list in place.
8. list.copy() : Return a shallow copy of the list. Equivalent to a[:]

### Set
- Python also includes a data type for sets.
- A set is an unordered collection with no duplicate elements.
- Basic uses include membership testing and eliminating duplicate entries.
- Set objects also support mathematical operations like union, intersection, difference, and symmetric difference.

Example:
```
a = set('abracadabra')
b= set('alacazam')
```

### Dictionaries
- Dictionaries consist of pairs (called items) of keys and their corresponding values.
- Keys must be immutable

Example:
```
dict = {'Alice': '2341', 'Beth': '9102', 'Cecil': '3258'}

del dict['Name']; # remove entry with key 'Name' 
dict.clear(); # remove all entries in dict
del dict ; # delete entire dictionary
```

### Tuples
- A Tuple is a collection of Python objects separated by commas. 
- In someways a tuple is similar to a list in terms of indexing, nested objects and repetition but a tuple is immutable unlike lists which are mutable.
- If a single element has to be stored in tuple then a trailing zero should be added i.e tuple = (hello,)
Example:
```
tup = ('python', 'example')
```
- Tuples are more efficient than lists (less memory consumtion than lists)
### Modules
- A module allows you to logically organize your Python code.
- Grouping related code into a module makes the code easier to understand and use.
- A module is a Python object with arbitrarily named attributes that you can bind and reference.
- Simply, a module is a file consisting of Python code.

Example:
```
def print_name( parameter ): 
  print ("Hello : ", parameter) 
  return
```

### Import statement
- We can use any Python source file as a module by executing an import statement in some other Python source file.
- The import has the following syntax:
```
import module1[, module2[,... moduleN]
```
- When the interpreter encounters an import statement, it imports the module if the module is present in the search path.
- A search path is a list of directories that the interpreter searches before importing a module.
- A module can define functions, classes and variables.
- A module can also include run able code.

### Built-in List Functions & Methods
1. abs(x) -	Return the absolute value of a number. The argument may be an integer or a floating point number.
2. bin(x) -	Convert an integer number to a binary string.
3. len(s) -	Return the length (the number of items) of an object. The argument may be a sequence (such as a string, bytes, tuple, list, or range) or a collection (such as a dictionary, set, or frozen set).
4. max(iterable, *[, key, default]) -	Return the largest item in an iterable or the largest of two or more arguments.
5. min(iterable, *[, key, default]) -	Return the smallest item in an iterable or the smallest of two or more arguments.
6. hash(object) - Return the hash value of the object (if it has one). Hash values are integers. They are used to quickly compare dictionary keys during a dictionary lookup. Numeric values that compare equal have the same hash value (even if they are of different types, as is the case for 1 and 1.0). hash() method used by on immutable object, if we use this on a mutable object like list, set, dictionaries then it will generate an error.

### Range function
- If we do need to iterate over a sequence of numbers, the built-in function range() comes in handy.
- It generates arithmetic progressions.

Example:
```
range(5, 10)
5 through 9

range(0, 10, 3)
0, 3, 6, 9

range(-10, -100, -30)
-10, -40, -70
```

### List Comprehensions
- List comprehensions provide a concise way to create lists.
- Common applications are to make new lists where each element is the result of some operations applied to each member of another sequence or iterable, or to create a subsequence of those elements that satisfy a certain condition.
- For example, assume we want to create a list of squares, like: [x**2 for x in range(10)]
- A list comprehension consists of brackets containing an expression followed by a for clause, then zero or more for or if clauses.
 Example:
 ```
[(x, y) for x in [1,2,3] for y in [3,1,4]]
[(1, 3), (1, 1), (1, 4), (2, 3), (2, 1), (2, 4), (3, 3), (3, 1), (3, 4)]
```

### Set Comprehensions
- Similarly to list comprehensions, set comprehensions are also supported
Example
```
 a = {x for x in 'abracadabra' if x not in 'abc'}
 {'r', 'd'}
```

### enumerate
- enumerate(iterable, start=0)
- Returns an enumerate object.
- enumerate essentially turns each element of the input list into a list of tuples with the first element as the index and the element as the second.
Example
```
seasons = ['Spring', 'Summer', 'Fall', 'Winter'] print(list(enumerate(seasons)))
[(0, 'Spring'), (1, 'Summer'), (2, 'Fall'), (3, 'Winter')]
```

### Scope
- Scope is the portion of the program from where a namespace can be accessed directly without any prefix. At any given moment, there are at least three nested scopes.
1. Scope of the current function which has local names
2. Scope of the module which has global names
3. Outermost scope which has built-in names

### globals() and local() functions

- If locals() is called from within a function, it will return all the names that can be accessed locally from that function.
- If globals() is called from within a function, it will return all the names that can be accessed globally from that function.
- The return type of both these functions is dictionary. Therefore, names can be extracted using the keys() function.

