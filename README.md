# 🔁 FOR LOOPS IN PYTHON
📌 Introduction

A for loop in Python is used to iterate over a sequence (such as a list, tuple, string, or range). It allows you to execute a block of code multiple times in a clean and readable way.

Python’s for loop is different from many other programming languages because it works directly with iterable objects.

# 🎯 Objectives

Understand what a for loop is

Learn the syntax of a for loop

Use range() with loops

Iterate over strings, lists, and tuples

Apply nested for loops

Use break, continue, and else with loops

# 🧠 Basic Syntax
for variable in sequence:
    # code block

variable → Temporary variable that takes each value from the sequence

sequence → List, tuple, string, range, etc.

Indentation is mandatory in Python

📘 Examples
1️⃣ Using range()
for i in range(5):
    print(i)

Output:

0
1
2
3
4
2️⃣ Loop Through a List
fruits = ["apple", "banana", "mango"]

for fruit in fruits:
    print(fruit)
3️⃣ Loop Through a String
for letter in "PYTHON":
    print(letter)
4️⃣ Using break
for i in range(10):
    if i == 5:
        break
    print(i)

👉 Stops the loop when i becomes 5.

5️⃣ Using continue
for i in range(5):
    if i == 2:
        continue
    print(i)

👉 Skips number 2.

6️⃣ Nested For Loop
for i in range(3):
    for j in range(2):
        print(i, j)
🔄 The else with For Loop
for i in range(3):
    print(i)
else:
    print("Loop finished")

The else block runs after the loop completes normally (without break).

🚀 Advantages of For Loop

Easy to read and write

Reduces repetitive code

Works efficiently with iterable objects

Useful in data processing and automation

# 📚 Conclusion

The for loop is one of the most important control structures in Python. It simplifies iteration and makes programs cleaner and more efficient. Mastering loops is essential for solving real-world programming problems.
