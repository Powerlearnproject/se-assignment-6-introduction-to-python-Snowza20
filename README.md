[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15314981&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is among the strongest and most adaptable programming languages,easy to learn, understand and it is widely used by developers.

Scalibility - extensively utilized in web development, data analysis, artificial intelligence ect.

Integration capabilities - suitable for developing complex multi-technology applications, able to interface with other languages like C, java ect.

Support for GUIs - support several frameworks PyQt, wxPython ect.

Expressive Language - enables programmers to write logical and understandable code for small/large projects.

Cross-platform - adaptable to various settings and supported by major operating systems.

Python frameworks like django and flask are widely utilized in web development
Because of python's libraries including data analysis it is extensively utilized in data science

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

- Access the official website https://www.python.org/.
 
- Go to the Downloads section on the menu.

- Click on the latest version to download

- Once the installer is downloaded, locate the downloaded file 

- Double-click the installer to start the installation process.

- Click checkbox for both install launcher for all users and add python to PATH
  
- Click on the customize installation button or continue with the default settings. 

- Click on the install now button to start the installation process. 
  
- The installer will now install Python onto your computer. 
  
- Once the installation is complete verify by opening a command prompt type python --version. 

- The installed Python version should diplay this confirms that python has been successfully installed.

- For virtual environment on command prompt use cd command to change directory to your project folder where you want to create the virtual environment cd path\to\your\project

- To create a new virtual environment using venv type the command python -m venv myenv
  
- To activate the virtual environment, navigate to the Scripts directory inside your virtual environment directory and run the activate script myenv\Scripts\activate

- After activation, you should see the virtual environment’s name (myenv) appear at the beginning of your command prompt.
  
  3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

# Simple Python program to print "Hello, World!"
print("Hello, World!")

Comments in python are represented with # intended for human readers to understand the code

print() function is used to output text to the console. 

 "Hello, World!" is the string passed as an argument to the print() function.
 
Strings can be enclosed in either single (') or double (") quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Integer (int) -  positive or negative whole numbers without any decimal point.

# Integer variable
age = 45
print(f"Age: {age}, type: {type(age)}")

Float (float) - real numbers with a decimal point.

# Float variable
height = 1.60
print(f"Height: {height}, type: {type(height)}")

Boolean (bool) - a value of truth, either True or False.

# Boolean variables
is_pre school learner = True
is_in highschool = False
print(f"Is a pre school learner? {is_pre school learner}, type: {type(is_pre school learner)}")
print(f"In highschool? {is_in highschool}, type: {type(is_in highschool)}")

String (str) - a sequence of characters enclosed within single quotes ' or double quotes ".

# String variable
name = "Josh"
print(f"Name: {name}, type: {type(name)}")

List -  ordered collection of items that can be of different data types.

# List variable
numbers = [1, 2, 3, 4, 5]
print(f"Numbers: {numbers}, type: {type(numbers)}")
print(f"First number in numbers list: {numbers[0]}")

Tuple - ordered collections of items elements cannot be changed after creation.

# Tuple variable
coordinates = (50, 60)
print(f"Coordinates: {coordinates}, type: {type(coordinates)}")
print(f"Second coordinate in coordinates tuple: {coordinates[1]}")

Set - unordered collection of unique items with no duplicate elements.

# Set variable
unique_numbers = {1, 2, 3, 4, 5}
print(f"Unique numbers: {unique_numbers}, type: {type(unique_numbers)}")

Dictionary (dict) -  collection of key-value pairs.

# Dictionary variable
person = {'name': 'John', 'age': 65, 'city': 'Cape Town'}
print(f"Person: {person}, type: {type(person)}")
print(f"Name: {person['name']}, Age: {person['age']}, City: {person['city']}")

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

Conditional statements enables you to run specific code depending on whether a condition is true or false.

# if-else statement to determine if a number is positive, negative, or zero

num = float(input("Enter a number: "))

if num > 10:
    print("The number is positive.")
elif num < 5:
    print("The number is negative.")
else:
    print("The number is zero.")

Loops are used to repeatedly run a block of code

# loop to iterate through a list of food
food = ["almonds", "brown rice", "yoghurt", "eggs"]

for food in food:
    print("I like", food)

# output
I like almonds
I like brown rice
I like yoghurt
I like eggs

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
  
functions are reusable code segments that carry out particular task defined by the 'def' keyword with the ability to take parameters as input and return a result optionally.

They are useful in dividing codes into blocks making it easier to read, reuse and mantain

def add_numbers(a, b):
    """Function to add two numbers and return the result."""
    return a + b

# Calling the add_numbers function with arguments 7 and 2
result = add_numbers(7, 2)
print("Sum:", result)  # Output: Sum: 9

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

# Lists

Are ordered collections of items.

Order of elements in a list is preserved and elements are accessed by their index which starts at 0.

Elements can be changed, added or removed after creating  a list.

Elements in a list can be integers, floats, strings, other lists, etc.

Elements are accessed using indexing ([] notation) and slicing ([:] notation).

Stores collection of data where the order of elements matter sequences, logs etc. When you need to access elements by their position or index.

# Dictionaries

Are unordered collections of key-value pairs.

Elements are accessed by keys.

Keys are unique within a dictionary.

Key-value pairs can be changed added or deleted.

Keys in a dictionary must be immutable (e.g., strings, numbers, tuples).


Values in a dictionary can be of any data type (integers, floats, strings, lists, other dictionaries, etc.).

Elements in a dictionary are accessed using keys ([] notation).

toring data where relationships between keys and values are important.
When you need to quickly look up values based on keys without caring about the order.

# Create a list of numbers
numbers = [1, 2, 3, 4, 5]

# Create a dictionary with key-value pairs
my_dict = {
    'mango': 5,
    'orange': 10,
    'pear': 3,
    'blueberries': 7
}

# Print the initial list and dictionary
print("Initial list of numbers:", numbers)
print("Initial dictionary:", my_dict)

# Perform basic operations on the list
numbers.append(6)
numbers.extend([7, 8])
numbers.remove(3)

# Perform basic operations on the dictionary
my_dict['mango'] = 6
del my_dict['pear']
my_dict['lemon'] = 9

# Print the modified list and dictionary
print("\nModified list of numbers:", numbers)
print("Modified dictionary:", my_dict)

# Access elements by index in the list
print("\nAccessing element by index in the list:")
for i in range(len(numbers)):
    print(f"Element at index {i}:", numbers[i])

# Access elements by key in the dictionary
print("\nAccessing elements by key in the dictionary:")
for key in my_dict:
    print(f"Value for '{key}':", my_dict[key])

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

The process of foreseeing and managing exceptions or runtime errors that might arise while a program is being executed improving program flow control and increases Python applications dependability and maintainability.

try:
    # Code that may raise an exception
    num1 = int(input("Enter a number: "))
    num2 = int(input("Enter another number: "))
    result = num1 / num2

except ZeroDivisionError:
    print("Error: Division by zero!")
    
except ValueError:
    print("Error: Invalid input! Please enter a valid integer.")

else:
    print("Division result:", result)
    
finally:
    print("Execution completed. Exiting...")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules in python is a method of structuring python code to make it easier to read and reuse with all of the functions, classes, variables, and definitions in a single file.

Packages in python is a method of using "dotted module names" to organize the module namespace, have the ability to arranged into subdirectories and hierarchical directories.

To import and use a module in your script use the 'import' statement followed by the name of the module.

# Importing the math module
import math

# Using functions from the math module
print("Value of pi:", math.pi)
print("Square root of 16:", math.sqrt(16))
print("Cosine of 0 radians:", math.cos(0))

10.    File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

By using the built-in functions and methods made available by the open() function and file objects to read from and write to files. 

# Open a file for reading
file_path = 'index.txt'
with open(file_path, 'r') as file:
    # Read the entire content of the file
    content = file.read()
    print("File content:\n", content)

# File is automatically closed after the 'with' block

# Open a file for writing
file_path = 'output.txt'
with open(file_path, 'w') as file:
    # Write data to the file
    file.write("Hello, World!\n")
    file.write("This is a testing text.")

print("Data has been written to", file_path)

# File is automatically closed after the 'with' block



https://www.pythontutorial.net/python-basics/

https://docs.python.org/3/

https://dev.to/realrichi3/syntax-and-semantics-5ac9

https://www.freecodecamp.org/news/variable-data-types-explained/

https://www.w3schools.in/python/loops

https://www.w3schools.com/python/python_functions.asp

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


