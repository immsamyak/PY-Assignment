# Python Assignment

Submitted by:
- **Name:** Samyak Chaudhary
- **Faculty:** BCSIT 
- **Semester:** 2nd
- **College:** KFA 

## What's in this Project?

This project contains Python programs that solve various programming problems. Think of it as a collection of small tools and puzzles that help learn Python programming. The problems are divided into two sets:

### Set A: Basic Stuff (The Fundamentals)
1. **Calculator**: A simple calculator that can add, subtract, multiply, and divide numbers
2. **Number Converter**: Converts regular numbers to binary (like converting 5 to 101)
3. **Age Checker**: Tells if someone is a kid, adult, or senior citizen
4. **Number Swapper**: Swaps two numbers without using extra space
5. **Fibonacci**: Prints the famous Fibonacci sequence (like 0,1,1,2,3,5,...)
6. **Prime Checker**: Tells if a number is prime or not
7. **Sum Checker**: Checks if two numbers add up to a third number
8. **Factorial**: Calculates factorial of a number (like 5! = 5×4×3×2×1)
9. **Safe Division**: Divides numbers while handling errors
10. **Max Finder**: Finds the biggest number in a list
11. **Greeter**: Says hello with your name and age
12. **Vowel Counter**: Counts how many vowels are in a word
13. **Times Table**: Shows multiplication tables
14. **Star Pattern**: Makes a triangle using stars (*)
15. **Pyramid**: Makes a pyramid using stars (*)

### Set B: Coding Challenges (The Fun Stuff)
1. **Palindrome**: Checks if a number reads the same forwards and backwards
2. **Unique Finder**: Finds the one unique number in a list of pairs
3. **Number Pairs**: Finds two numbers that add up to a target
4. **Happy Numbers**: A fun math puzzle about "happy" numbers
5. **Duplicate Checker**: Checks if any number appears twice in a list

## How to Use This?

1. Make sure you have Python installed on your computer
2. Open the `Assignment.ipynb` file using Jupyter Notebook
3. Run each program one by one
4. Type in numbers or text when asked

## What You Need
- Python 3
- Jupyter Notebook

That's it! Each program is like a small tool that helps learn different parts of Python programming. Have fun trying them out! 😊

## File Structure

```
.
├── Assignment.ipynb    # Main Jupyter notebook containing all exercises
├── factorial_module.py # Custom module for factorial calculation
└── README.md          # This documentation file
```

## Set A: Basic Programming Exercises

1. **Basic Calculator**
   - Implements a simple calculator performing addition, subtraction, multiplication, and division
   - Handles division by zero case

2. **Decimal to Binary Converter**
   - Converts decimal numbers to their binary equivalent
   - Uses Python's built-in bin() function

3. **Age Category Classifier**
   - Takes age as input
   - Classifies person as minor (<18), adult (18-59), or senior (≥60)

4. **Variable Swap**
   - Swaps values of two variables without using a third variable
   - Uses Python's tuple unpacking

5. **Fibonacci Series**
   - Prints first 10 numbers of the Fibonacci series
   - Uses efficient variable swapping technique

6. **Prime Number Checker**
   - Checks if a given number is prime
   - Implements basic prime number algorithm

7. **Sum Checker**
   - Takes three numbers as input
   - Checks if third number equals sum of first two

8. **Factorial Calculator**
   - Uses custom module (factorial_module.py)
   - Calculates factorial of a given number

9. **Division Handler**
   - Performs division of two numbers
   - Includes zero division error handling

10. **Maximum Number Finder**
    - Takes a list of numbers
    - Returns maximum value using max() function

11. **Greeting Function**
    - Takes name and optional age parameter
    - Demonstrates default parameter usage

12. **Vowel Counter**
    - Counts number of vowels in a given string
    - Case-insensitive counting

13. **Multiplication Table**
    - Prints multiplication table up to 10
    - Uses f-strings for formatting

14. **Right Triangle Pattern**
    - Prints right-angled triangle using asterisks
    - Demonstrates pattern printing

15. **Pyramid Pattern**
    - Prints pyramid pattern using asterisks
    - Shows advanced pattern printing

## Set B: LeetCode Problem Solutions

1. **Palindrome Number**
   - Checks if a number is palindrome
   - LeetCode problem implementation

2. **Single Number**
   - Finds non-duplicate number in array
   - Uses XOR operation for efficient solution

3. **Two Sum**
   - Finds two numbers that add up to target
   - Basic implementation with nested loops

4. **Happy Number**
   - Determines if a number is "happy"
   - Uses set to detect cycles

5. **Contains Duplicate**
   - Checks for duplicates in array
   - Uses set comparison for efficiency

## Custom Modules

### factorial_module.py
```python
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result
```
- Custom module for factorial calculation
- Used in exercise 8 of Set A

## Usage

1. Make sure you have Python and Jupyter Notebook installed
2. Open `Assignment.ipynb` in Jupyter Notebook
3. Run cells sequentially to see the output
4. Input values when prompted

## Requirements

- Python 3.x
- Jupyter Notebook
- Basic Python packages (all built-in) 