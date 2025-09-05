**Name: Tahmina Khan
ID: 7993646

### Create a Python script that incorporates the following tasks:

1. **Comments Practice**:
   - Include at least three different types of comments: single-line comments, multi-line comments, and comments within code lines.
  
  # This is a single-line comment explaining the purpose of the program def calculate_area(radius):

    """
    This is a multi-line comment (docstring) explaining
    the function. It calculates the area of a circle given the radius.
    """
    
    pi = 3.14159  # Pi value used for calculation
    area = pi * radius ** 2  
    # Formula to calculate area of a circle return area

# Calling the function
circle_radius = 5  # Radius of the circle
circle_area = calculate_area(circle_radius)  # Calculate area using the function
print("The area of the circle is:", circle_area)  
# Output the result

2. **String Concatenation**:
   - Take two strings as input from the user and concatenate them into one string. Print the resulting string.

# This program concatenates two strings entered by the user

# Taking input from the user
string1 = input("Enter the first string: ")  # First string input
string2 = input("Enter the second string: ")  # Second string input

# Concatenating the two strings
result = string1 + string2  # '+' operator joins the two strings

"""
Multi-line comment:
The program now prints the concatenated result.
This shows how the two input strings are combined.
"""
print("The concatenated string is:", result)  
# Output the final result

3. **Simple Calculation**:
   - Take two numbers as input from the user.
   - Perform addition and multiplication on these numbers.
   - Print the results of both operations.

# This program takes two numbers from the user and performs addition and multiplication

# Taking input from the user
num1 = float(input("Enter the first number: "))  # First number input
num2 = float(input("Enter the second number: "))  # Second number input

# Performing calculations
sum_result = num1 + num2  # Addition of the two numbers
product_result = num1 * num2  # Multiplication of the two numbers

"""
Multi-line comment:
The program now prints both results.
First, it shows the sum, then the product of the two numbers.
"""

print("The sum of the numbers is:", sum_result)  # Output the addition result
print("The product of the numbers is:", product_result)  
# Output the multiplication result

4. **Exponent Calculation**:
   - Calculate the square of one of the numbers entered by the user in the previous step.
   - Print the result.

 # This program calculates the square of a number entered by the user

# Taking input from the user
number = float(input("Enter a number to find its square: "))  # User input for calculation
# Calculating the square
square = number ** 2  # '**' operator raises the number to the power of 2

"""
Multi-line comment:
The program now prints the square of the number.
This demonstrates the use of exponentiation in Python.
"""

print("The square of", number, "is:", square)  
# Output the square result

5. **Modulo Practice**:
   - Find the remainder when the first number is divided by the second number entered by the user.
   - Print the result.

# This program calculates the remainder when the first number is divided by the second number

# Taking input from the user
num1 = float(input("Enter the first number: "))  # First number input
num2 = float(input("Enter the second number: "))  # Second number input
# Calculating the remainder
remainder = num1 % num2  # '%' operator gives the remainder of division

"""
Multi-line comment:
The program now prints the remainder.
This demonstrates how the modulo operator works in Python.
"""

print("The remainder when", num1, "is divided by", num2, "is:", remainder)  
# Output the remainder
