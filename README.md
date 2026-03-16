# list-filter-tool
List Filtering Program (Python)

This project is a command-line list filtering tool written in Python and developed using Jupyter Notebook / Google Colab.

The program accepts a list of user inputs and allows filtering based on several conditions such as numeric comparisons, even/odd numbers, string length, and removing empty values.

This project was created to practice programming logic, loops, and conditional filtering without relying heavily on built-in shortcuts.

Features

The program supports the following filtering operations:

Find numbers greater than a specific value

Find even numbers

Find odd numbers

Find strings longer than a specified length

Remove empty values from a list

Example Workflow
Input

User enters a list of items:

Enter items separated by space:
10 25 7 42 15
Menu
1) Find value greater than a certain number
2) Find Even Numbers
3) Find Odd Numbers
4) Find String longer than certain length
5) Remove Empty Values
Example Output

If option 1 is selected and the value is 10:

[25, 42, 15]
How It Works

The program follows this process:

User inputs a list of elements.

The input string is converted into a Python list.

The user selects a filtering option.

The program iterates through the list using loops.

Elements meeting the condition are added to a new filtered list.

The filtered result is displayed.

Concepts Practiced

This project focuses on practicing core programming concepts such as:

Lists

Loops (for)

Conditional statements (if)

Functions

Basic filtering algorithms

Menu-driven programs

Input handling

File Structure
list-filtering-tool
│
├── ListFiltering.ipynb
└── README.md

The main logic is implemented inside the Jupyter Notebook file.

Running the Program

You can run the notebook in:

Google Colab

Jupyter Notebook

Any Python environment supporting .ipynb files

Steps:

Open the notebook

Run the cells

Enter your list when prompted

Choose a filtering option

Future Improvements

Possible improvements include:

Support for mixed data types

Advanced filtering rules

Sorting filtered results

Counting removed elements

Improved input validation

Converting the program into a full CLI tool

Learning Purpose

This project was created for learning and practicing algorithmic thinking in Python, especially list filtering logic without relying heavily on built-in methods.
