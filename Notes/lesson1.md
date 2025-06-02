**Input and Output**
```python
# Output
print("Hello world!")

# Input
name = input("Enter your name: ")
print("Hello", name)
```
- This is how we output to our user and also take input from our user in python.

**Comments**
```python
# This is a single line comment

"""
This is a 
multi-line comment.
"""
```
- Remember that a comment is something for creators to document and read, python ignores comments, it's as if they were never there!

**Variables**
```python
# Variable assignment
x = 10 # This is called an integer
name = "Alice" # This is called a string
pi = 3.14 # This is called a double
isValid = True # This is called a boolean
```
- These are the main variables in python. You might be familiar with them through some of your math classes!

**Math - Operators**
- Arithmetic: +, -, * (multiplication), / (divide), //, % (remainder), **
- Comparison: ==, !=, >, <, >=, <=
- Logical: and, or, not
- Assignment: =, +=, -=, *=, etc.

```python
a = input("Enter first number: ") # Takes a string from the user
b = input("Enter second number: ") # Takes a string from the user
c = int(a) # Makes a into a number
d = int(b) # Makes b into a number

# e = c + d # Adds c and d
# e = c - d # Minus a and b
# e = c * d # Multiplies c by d
e = c / d # Divides c by d

print(e)
```


**Simple Program - Lesson 1**
```python
# Ask for user's name
name = input("What is your name? ") # name variable is a string

# Ask for user's age
age = int(input("How old are you? ")) # since age is anumber we convert to int

# Calculate future age
future_age = age + 10

# Print a message
print(f"Hello, {name}! In 10 years, you will be {future_age} years old.")
```


**Conditional Statements**
- You want to run a program which involves restricitons or conditions.

```python
"""
Situation: Let's say you wanted to go to the movies and there is a new movie that
came out called, Scary Movie 5. Now this movie is extremely scary, and thus there
is a age restriction on who could buy the tickets. The restriction/condition is
that you have to be 18 or over to buy the tickets. Now a days, everything is done
by a computer, so you input your age on a ipad at the front of the movie theather.

We will be creating the program which verifies your age before you get your ticket.
"""

age = int(input("How old are you?\n"))

if age >= 18: # if age is greater equal than 18, do the following
    print("Hey you are an adult, and therefore you can buy a ticket. Head on in!")
elif age >= 13: # if the age is greater equal than 13, but less than 18, do the following
    print("You are a teenager, and therefore you have to ask a parent to buy the tickets.")
else:
    print("You are not allowed. Maybe watch the new paw patrol movie.")
```

**While Loop**

Here is a program we created. Which loops over a count variable over and over again, untill
it reaches the number 5. Then we print a statement, and end the program.

```python
# A loop is something which repeats over and over again

# While loop: A loop that is infinite in nature, and stops until
# another condition is met.

count = 0 # count is our condition

while count < 5: # if count is less than 5, then proceed.
    print(count) # prints the current count
    count = count + 1 # we add 1 to count


print("Now the program is done")
```
