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

### for loop
- A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).
- This is less like the for keyword in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.
- With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.
