# Python Stack

## Explanation

A Stack is a linear data structure that follows the **LIFO (Last In, First Out)** principle.

The element inserted last is removed first.

Example:

```text
Push: 10 → 20 → 30

Pop: 30
```

This program implements a stack using a Python list.

## Problem Statement

Write a Python program to implement a Stack using a list.

The program should support:

* Push
* Pop
* Peek
* Display

## Features

* Implements Stack using a list
* Follows LIFO principle
* Supports push operation
* Supports pop operation
* Supports peek operation
* Displays stack elements
* Handles an empty stack

## How It Works

1. An empty list is created to represent the stack.
2. `push()` adds an element to the top of the stack.
3. `pop()` removes the top element.
4. `peek()` displays the top element without removing it.
5. `display()` shows all elements in the stack.
6. A menu allows the user to select an operation.

## Technologies Used

* Python 3

## Data Structure Used

* Stack
* List

## Methods Used

* `append()`
* `pop()`
* `input()`
* `len()`

## Program Flow

1. Create an empty stack.
2. Display the menu.
3. Read the user's choice.
4. Perform the selected operation.
5. Continue until the user chooses Exit.

## Sample Input

```text
1. Push
2. Pop
3. Peek
4. Display
5. Exit

Enter your choice: 1
Enter element: 10

Enter your choice: 1
Enter element: 20

Enter your choice: 4
```

## Sample Output

```text
Stack: [10, 20]
```

For a pop operation:

```text
Enter your choice: 2
Popped element: 20
```

## Time Complexity

* Push: O(1)
* Pop: O(1)
* Peek: O(1)
* Display: O(n)

## Space Complexity

* O(n)

## Key Learning

* Understanding Stack
* Understanding LIFO
* Implementing stack operations
* Using Python lists as a stack
* Handling an empty stack
* Understanding time complexity

## File Location

```text
Python-Stack/stack.py
```

## Repository Structure

```text
Python-Stack/
│
├── stack.py
└── README.md
```

## Author

V.Harini
