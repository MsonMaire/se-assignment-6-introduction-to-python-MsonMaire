SE-Assignment-6

Assignment: Introduction to Python

1. Python Basics:
Python is a high-level, interpreted programming language known for its simplicity and readability. Some key features include:

Easy to Learn and Use: Python's syntax is clear and expressive, making it accessible for beginners.
Versatility: Python supports multiple programming paradigms (procedural, object-oriented, functional) and has a vast standard library.
Community and Support: It has a large community of developers contributing libraries and frameworks.
Use Cases: Python is used in web development (Django, Flask), data analysis (Pandas, NumPy), artificial intelligence (TensorFlow, PyTorch), and automation (scripting).

2. Installing Python:
To install Python:

Windows: Download the installer from python.org, run it, and select "Add Python to PATH". Verify with python --version in Command Prompt. Use python -m venv env_name to set up a virtual environment.
macOS: Install via Homebrew (brew install python) or download from python.org. Verify with python3 --version in Terminal. Use python3 -m venv env_name for a virtual environment.
Linux: Use the package manager (e.g., apt, yum) to install Python. Verify with python3 --version in the terminal. Use python3 -m venv env_name for a virtual environment.

3. Python Syntax and Semantics:

# hello_world.py
print("Hello, World!")

Explanation:
print() is a built-in function to output text.
"Hello, World!" is a string literal enclosed in double quotes.

4. Data Types and Variables:
Basic data types in Python:

Integer (int): Whole numbers.
Float (float): Numbers with a decimal point.
String (str): Ordered sequence of characters.
Boolean (bool): True or False.
python

# data_types.py
num = 10
pi = 3.14
name = "Alice"
is_python_fun = True

5. Control Structures:
Conditional statements (if-else):

# conditional.py
age = 20
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
Loops (for loop):

# loops.py
for i in range(1, 5):
    print(i)

6. Functions in Python:
Functions are reusable blocks of code. They improve code organization and reuse.

# sum_function.py
def add_numbers(a, b):
    return a + b

result = add_numbers(3, 5)
print("Sum:", result)

7. Lists and Dictionaries:
Lists: Ordered collection of items.
Dictionaries: Key-value pairs.

# lists_and_dicts.py
numbers = [1, 2, 3, 4]
person = {'name': 'Alice', 'age': 25}

print(numbers[0])  # Accessing list element
print(person['name'])  # Accessing dictionary value

8. Exception Handling:
Exception handling manages errors gracefully.

# exception_handling.py
try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
finally:
    print("Execution complete.")

9. Modules and Packages:
Modules: Python files containing functions, classes, and variables.
Packages: Collection of modules organized in directories.

# using_math_module.py
import math

print(math.sqrt(25))  # Example of using math module function

10. File I/O:
Reading from a file:

# read_file.py
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)
Writing to a file:

# write_file.py
data = ["Apple", "Banana", "Cherry"]

with open('fruits.txt', 'w') as file:
    for fruit in data:
        file.write(fruit + '\n')

**Sources/ References**

- Python.org
- ChatGPT
