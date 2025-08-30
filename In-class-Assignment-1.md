### Student Info:
Name: Tahmina Khan 
ID:7993646


### Problem 1: Comment Practice

**Problem:** Create a Python script that contains at least three different types of comments: single-line comments, multi-line comments, and comments within code lines.

# This is a single-line comment

# The program will perform simple math operations

"""
This is a multi-line comment.
We can use it to explain sections of the code or provide longer documentation.
"""

# Define a function to add two numbers

def add_numbers(a, b):

    return a + b  # return the sum of a and b

# Define a function to subtract two numbers
def subtract_numbers(a, b):

    return a - b  # return the difference of a and b

# Main execution
if __name__ == "__main__":

    x = 10  # first number
    y = 5   # second number

# Perform operations

    sum_result = add_numbers(x, y)
    diff_result = subtract_numbers(x, y)

# Print results

    print("Sum:", sum_result)        
    # Output should be 15
    print("Difference:", diff_result)  
    # Output should be 5

### Problem 2: String Concatenation

**Problem:** Write a Python program that takes two strings as input and concatenates them into one.

# Take input from the user

string1 = input("Enter the first string: ")
string2 = input("Enter the second string: ")

# Concatenate the two strings
result = string1 + string2

# Display the result
print("Concatenated string:", result)


### Problem 3: Simple Calculation

**Problem:** Write a Python program that takes two numbers as input and performs addition and multiplication on them.

# Take input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

# Perform addition
addition = num1 + num2

# Perform multiplication
multiplication = num1 * num2

# Display the results
print("Addition:", addition)
print("Multiplication:", multiplication)


### Problem 4: Exponent Calculation

**Problem:** Write a Python program that calculates the square of a number entered by the user.

# Take input from the user
num = float(input("Enter a number: "))

# Calculate the square

square = num ** 2

# Display the result
print("The square of", num, "is:", square)


### Problem 5: Modulo Practice

**Problem:** Write a Python program that takes two numbers as input and finds the remainder when the first number is divided by the second number.

# Take input from the user
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))

# Calculate remainder
remainder = num1 % num2

# Display result
print("The remainder when", num1, "is divided by", num2, "is:", remainder)

