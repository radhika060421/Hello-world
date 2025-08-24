🐍 Python Notes
📌 Basics
# Hello World
print("Hello, world!")


Variables: x = 10

Data Types: int, float, str, bool, list, tuple, set, dict

Comments: # Single line and ''' Multi-line '''

🔁 Control Flow
Conditional Statements
if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")

Loops
# for loop
for i in range(5):
    print(i)

# while loop
while x > 0:
    x -= 1

🧰 Functions
def greet(name):
    return f"Hello, {name}"


*args: Variable length arguments

**kwargs: Keyword arguments

🗂️ Data Structures
Lists
my_list = [1, 2, 3]
my_list.append(4)

Tuples
my_tuple = (1, 2, 3)

Sets
my_set = {1, 2, 3}

Dictionaries
my_dict = {"name": "Alice", "age": 25}

🧵 Object-Oriented Programming (OOP)
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print(f"Hi, I'm {self.name}")

🧪 Exception Handling
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Done")

📁 File Handling
with open("file.txt", "r") as f:
    content = f.read()

📦 Modules and Packages
import math
print(math.sqrt(16))

🔍 Useful Built-ins

len(), type(), isinstance(), range(), enumerate(), zip(), map(), filter(), sorted()

🧪 Virtual Environments
python -m venv env
source env/bin/activate  # Linux/macOS
env\Scripts\activate     # Windows
