# Python_Practice

# 1) **Introduction**  
Python is one of the world's easiest and most popular programming languages. This course will teach you the basics of Python, without requiring prior knowledge.
   #### Ex) print("Hello Python!")
![image](https://github.com/user-attachments/assets/7517714a-2028-494d-abe9-24f0c584c69c)

### A) Hello World!
The "Hello World!" is a simple program that outputs Hello World! to the screen. In Python, we use print() to show words on the screen. The words go inside quotation marks. Let's take a look at the "Hello World!" program in Python
   #### Ex) print("Hello World!")
   ![image](https://github.com/user-attachments/assets/f8a44d8f-1626-423d-9880-4f0b4b95588b)
   
# 2) Variables 
### A) Numbers
Variables are containers that hold data values. They are used to store, manipulate, and display information within a program.
In short a variable is like a memory unit that we can access by typing the name of the variable. Each variable has a unique name and a value that can be of different types. Python is capable of automatically detecting the variable type, which makes coding more efficient.
#### Ex) variable_name = value
![image](https://github.com/user-attachments/assets/e83b74cf-a3fd-44a1-9650-7bf8dd96a054)

### B) String
A char is a single character (For example: 1, 6, %, b, p, ., T, etc.) The str (string) type is a special type that consists of multiple chars. To initialize a string value in a variable, enclose it within single or double quotation marks
#### Ex) S1 = 'This is a string' , S2 = "This is also a string"
![image](https://github.com/user-attachments/assets/5fde1886-b35e-4bd3-8871-2e5a78667951)


### C) Boolean
A bool (Boolean) type has only 2 possible values: True or False.
To assign a bool value to a variable,
#### Ex) variable_true = True , variable_false = False
In the above example, two variables named variable_true and variable_false are initialized, with the values True and False respectively.

![image](https://github.com/user-attachments/assets/7445e61d-6430-4a97-82a4-7ed275b9110e)

# 3) Operators
### A) Arithmetic operators
Operators used to perform operations on values. First we will discuss the most basic arithmetic operators, they may be familiar from math classes.

![image](https://github.com/user-attachments/assets/3b42bd7e-a4e2-4f3e-befc-9b4f1b9a4b68)

Let's see usage example, 
a = 3
b = 5
c = a + b # c holds 8

![image](https://github.com/user-attachments/assets/45a6a8fb-6df4-4c24-aec7-da135840150b)

![image](https://github.com/user-attachments/assets/cb869c11-47fc-435c-af73-9e2e070ddcd3)

### B) Arithmetic shortcuts
Python created a cool shortcut for self-arithmetic operations.

For example instead of writing:

![image](https://github.com/user-attachments/assets/8ec9232c-0d5e-4994-9ec3-a6e208ae19b4)

We can simplify it by writing +=:

![image](https://github.com/user-attachments/assets/fb36403b-25fb-4296-bc72-165670dc1fee)

The += is adding to a itself the value 3

This operation is valid for all arithmetic operations:

![image](https://github.com/user-attachments/assets/dc9fc9f8-6d95-429b-a41e-4238b75e455b)

### C) Comparison Operators
Comparison operators are used to compare between two operands. Sometimes we need to check whether an operand is bigger/smaller/... than another operand. The following table shows possible operators for comparison:

![image](https://github.com/user-attachments/assets/756fa102-bb3e-4cb7-806d-d242b93af8a8)

The comparison operator returns True if the comparison is correct or False otherwise.

![image](https://github.com/user-attachments/assets/9aec9145-2c8b-4059-bd43-f082d282b934)

var3 will hold True because var1 and var2 are not equal

### D) Logical Operators Part 1
Logical operators are used to check combinations of comparisons that return True or False.
For example, the following statement contains two comparisons: 
Is 5 greater than 3 and lesser than 6?

![image](https://github.com/user-attachments/assets/20a11ac2-8a54-433c-8704-5698377c5cc8)

Let's see some examples,

5 is bigger than 3 and 1 equals 1,

![image](https://github.com/user-attachments/assets/f2f0e7a6-2927-4c21-aab0-9a36474c6356)

Explanation: All of the operands are True, so b1 will hold True (and operation is True if both operands are True).

5 is not equals 4 or five equals 2,

![image](https://github.com/user-attachments/assets/8d909b72-e5ac-4c96-8a42-0509b0f87876)

Explanation: The first operand (5 != 4) is True so b2 is also True (or operation is True if either one of the operands is True)

1 is not equals 1 or false,

![image](https://github.com/user-attachments/assets/9883570d-d08f-48c8-b6d1-61435792599d)

Explanation: All of the operands are False, so b3 will hold False (or operation).


not (3 bigger than 4),

![image](https://github.com/user-attachments/assets/2654b4e6-2693-480c-854b-8e67eebc4171)

Explanation: The operand is False, so b4 will hold True (not operation).

not (5 bigger than 10 or 5 bigger than 1),

![image](https://github.com/user-attachments/assets/178d8920-19f7-4ae8-b82f-d8cd63033fd9)

Explanation: 5 > 10 or 5 > 1 is True (one of the operands is True), so in total b5 is False (not operation).



### E) Logical Operators Part 2

Logical operators have a special table called "Truth table" that shows what the combination of logical operators returns.

The truth table for the and operator:

![image](https://github.com/user-attachments/assets/000f1b68-85fc-498e-a1f1-c77e0e31ac1c)


The only way to get a True for the and operator is if both a and b are True

The truth table for the or operator:


![image](https://github.com/user-attachments/assets/cca5c993-5058-4a91-9826-624a302a422a)


In this case, to get a True result, either a or b should be True.

The truth table for the not operator:

![image](https://github.com/user-attachments/assets/680b964d-db68-4e52-ac57-a17415af01bf)

Here the value of a is reversed. If a is False then not a is True

# 4) Decision Making 

### A) If Statement

If statements allow us to execute code with conditions.

For example, let's look at the following code:

![image](https://github.com/user-attachments/assets/ff8e99aa-7df9-4af7-b894-5126145a9afe)

The above code checks whether the age variable is bigger than 18. If it is, it will set status to hold "Adult" string.

In the end, the code will increment age by 1 whether the age is bigger than 18 or not.

To use an if statement we need to add a colon : at the end of the if, and everything that is inside the if is indented with 4 spaces:

![image](https://github.com/user-attachments/assets/1bc5070c-4801-452a-9ea5-ac4c3c9e57d5)

If the condition is True, we will enter the code block inside the if (The indented code)

### B) If - Else

if allows us to execute particular code if a condition is met, but what if we want to execute something else if the condition is not met?

For that we have the else statement:

![image](https://github.com/user-attachments/assets/a41d6803-4955-4000-8d13-e8df4d737789)

In the above example, age is smaller than 18 which means it enters the else code and the status will hold "Young".

We can even make it more profound using the elif statement:

![image](https://github.com/user-attachments/assets/d3f271a3-ad9e-499a-8f85-6f4fa855078c)

Here it checks whether age is smaller than 18, if not it will continue to the next condition and check whether age is between 18 and 65. If that condition is also not met it will set status to "Old".

We can add as many elif statements as we want:

![image](https://github.com/user-attachments/assets/168b9001-5252-4816-9f03-3145d1b0388a)

# 5) Basic IO

### A) Output

In Python to print something to the screen we use print()

For example,

![image](https://github.com/user-attachments/assets/d736b3cb-d68a-4ec4-ac01-b4a4c75c79e3)

The above example prints "Hello" to screen.

Recall that you must enclose what you want to print with "" or with '', it is a string inside the print().

### B) Output with Variables

As of now we learned how to print simple strings, but sometimes we need to insert variables values into the string.

For example:

![image](https://github.com/user-attachments/assets/49caf3d9-d999-4496-9917-031331d48f5c) 

This will print "His age is: age" instead of "His age is: 10"

to make it work we will use the f string f"":

![image](https://github.com/user-attachments/assets/da98aa75-0a61-4215-aac9-cf4a0ea07db2)

This prints "His age is: 10"

Before the quotation marks "" we add the letter f and inside the string wherever we put parenthesis {} it will insert the value of what is written inside it.








