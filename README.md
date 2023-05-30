# GLAB-370.1.3-Looping-Adventures

## Welcome to the "Looping Adventures" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on a thrilling journey into the world of **loops** in Python. Get ready to explore the power of repetition and discover exciting ways to use loops!

### Prerequisites

Before we begin, make sure you have the following:

- Basic knowledge of Python syntax.
- A Python interpreter or an integrated development environment (IDE) installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: The Mighty "for" Loop](#step-2-the-mighty-for-loop)
- [Step 3: Looping through Lists](#step-3-looping-through-lists)
- [Step 4: The Adventurous "while" Loop](#step-4-the-adventurous-while-loop)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's begin by understanding what a **loop** is. A loop allows us to repeat a block of code multiple times. It's like setting off on an adventure and exploring new territories with each iteration!

### Step 2: The Mighty "for" Loop

In Python, the most commonly used loop is the **for loop**. It iterates over a sequence of elements and executes a block of code for each item in the sequence.

The general structure of a for loop in Python is:

```python
for item in sequence:
    # Code to be executed for each item
```

Let's try it out!

```python
# Example:
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

### Step 3: Looping through Lists

One of the fantastic features of for loops is the ability to iterate through lists. We can perform actions on each item in the list or access their indices for more control.

```python
# Example:
numbers = [1, 2, 3, 4, 5]

for num in numbers:
    print(num)

for index, num in enumerate(numbers):
    print("Index:", index, "Number:", num)
```

### Step 4: The Adventurous "while" Loop

Another type of loop in Python is the **while loop**. It continues executing a block of code as long as a specified condition remains true. It's like venturing into the unknown until a certain condition is met!

The general structure of a while loop in Python is:

```python
while condition:
    # Code to be executed as long as the condition is true
```

Let's explore!

```python
# Example:
count = 0

while count < 5:
    print("Count:", count)
    count += 1
```

### Step 5: Challenge

Now it's time for an adventurous challenge! Write a program that asks the user to enter a positive integer and then prints all the even numbers from 2 up to that number.

### Step 6: Conclusion

Congratulations on completing the "Looping Adventures" guided lab! You've mastered the art of loops and explored the realms of repetition in Python.

Remember to keep practicing and experimenting with loops. They are powerful tools that can save you time and open new doors in your coding journey!

Feel free to reach out if you have any questions. Good luck with your future coding adventures! 🎉
