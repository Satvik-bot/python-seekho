# Python Learning Series for Data Enthusiasts

Welcome! 
Each exercise builds on the basics, encouraging you to create solutions rather than just follow along.

## How to Use These Exercises

- Each folder contains a **challenge**.
- Read the instructions in `exercise.txt`.
- Complete the `solution.py` file.
- Some challenges require you to create a new script based on given data.

## Python Basics You Need to Know

### 1. Printing and Variables
```python
name = "Alice"
print(f"Hello, {name}!")
number = 1
print(number + 1)
```

### 2. Reading a File
```python
with open("data.txt", "r") as file:
    content = file.read()
    print(content)
```

### 3. Lists & Dictionaries (Handling Data)
```python
students = ["Alice", "Bob", "Charlie"]
grades = {"Alice": 90, "Bob": 85, "Charlie": 95}

print(students[0])  # First student
print(grades["Alice"])  # Alice's grade
```

### 4. Functions & Loops
```python
def greet(name):
    return f"Hello, {name}!"

for student in students:
    print(greet(student))
```

### 5. Classes & Objects
```python
class Student:
    def __init__(self, name, grade):
        self.name = name
        self.grade = grade

alice = Student("Alice", 90)
print(alice.name, alice.grade)
```

### 6. Connecting Python to SQL
```python
import sqlite3

connect = sqlite3.connectect("example.db")
cursor = connect.cursor()

cursor.execute("CREATE TABLE IF NOT EXISTS students (name TEXT, grade INTEGER)")
cursor.execute("INSERT INTO students VALUES ('Alice', 90)")
connect.commit()

cursor.execute("SELECT * FROM students")
print(cursor.fetchall())

connect.close()
```

Links : 
[Python to SQL](https://docs.python.org/3/library/sqlite3.html)
---
