# Experiment: Study of Iterative Structures (Loops) in Python

## Aim :
The primary aim of this practical is to study and implement different types of loops in Python. The experiment focuses on understanding how to automate repetitive tasks and solve complex logic problems using iterative structures.

## Objects :
Our main objectives were:

To master the While Loop for condition-based iteration.
To master the For Loop for range-based and sequence-based iteration.
To understand Nested Loops for solving multi-dimensional problems like matrix multiplication and combinations.
To learn loop control statements like break and continue to modify the flow of an iteration.

## Theory and Concepts Used

### 1. The While Loop
A while loop is used when we want to repeat a block of code as long as a specific condition is true. In this practical, I used it for simple counting and for reversing strings to check for palindromes. It is essential when the number of iterations isn't known beforehand.

### 2. The For Loop
The for loop is used to iterate over a sequence (like a list or a string) or a range of numbers. It is the most common loop used in Python for fixed-length iterations, such as generating Armstrong numbers within a specific range.

### 3. Loop Control: The continue Statement
Sometimes we need to skip a specific part of a loop without stopping the whole thing. The continue statement allows the program to jump back to the start of the loop for the next iteration, skipping any code written below it for that specific turn.

### 4. Nested Loops
When a loop is placed inside another loop, it is called a nested loop. This is a powerful concept used in this experiment for:

Matrix Multiplication: Iterating through rows and columns.
Combinations: Generating all possible sets of three digits.
Pattern Printing: Managing spaces and stars to create a diamond shape.

## Problem :
Write a Python program for matrix multiplication (if possible)

### Algorithm & Explanation:
Start by taking the number of rows and columns for two matrices A and B.
Check Condition: If columns of A do not equal rows of B, multiplication is impossible.
If valid, take user input to fill both matrices using nested loops.
Create a result matrix filled with zeros.
Use a triple-nested loop (i, j, k) to multiply elements and add them to the result matrix.
Print the final result in a structured grid format.

## Problem :
Write a Python code for Floyd's series

### Algorithm & Explanation:
Step 1: Start the program and take the number of layers (n) as input from the user.
Step 2: Initialize a variable a with the value 1 to act as the starting number of the series.
Step 3: Start an outer for loop that runs from 0 to n to manage the total number of rows.
Step 4: Inside the outer loop, start a nested for loop that runs i times to control the number of elements in the current row.
Step 5: Print the current value of a followed by a space.
Step 6: Increment the value of a by 1 after each print.
Step 7: Move to a new line after the inner loop finishes.
Step 8: Terminate the program once all iterations of the loops are complete.

## Problem Statement :
Write a code to print all the prime numbers in given range.

### Algorithm & Explanation:
Step 1: The outer loop picks a number from the user's range.
Step 2: The inner loop tries dividing that number by every integer from 2 up to num - 1.
Step 3: If the remainder is 0, it means the number is not prime and we stop checking.
Step 4: If no divisor is found, print the number as prime.

## Problem :
Write a code to print Diamond shape

### Algorithm & Explanation:
Step 1: Initialize a variable to determine the size of the diamond.
Step 2: Use the first loop to handle the top half of the diamond.
Step 3: Print required spaces and stars accordingly.
Step 4: Use the second loop to print the bottom half.
Step 5: Continue until the full diamond is printed.

## Problem:
Write a code to print 2D plane with stars symbol(*)

### Algorithm & Explanation:
Step 1: Initialize a variable to define the number of rows.
Step 2: Start a loop that runs for the given number of rows.
Step 3: Print increasing spaces in each iteration.
Step 4: Print a fixed number of stars in each row.
Step 5: End the program after all rows are printed.

## Practical Applications Implemented

Basic Counter — while — Incrementing a variable until it reaches N.
Palindrome Checker — while — Reversing a string using a loop.
Iterative Skip — while + continue — Skipping a specific value during iteration.
Matrix Multiplication — Triple for loops — Using i, j, k loops to calculate multiplication.
Digit Combinations — Triple for loops — Generating permutations of numbers.
Armstrong Finder — for — Iterating through a range and calculating sum of powers.
Diamond Pattern — for — Using two loops to print upper and lower halves.

## Conclusion
Through this experiment, I gained a deep understanding of how loops work in Python. I implemented simple counters, conditional skips, and complex nested structures like matrix multiplication. Understanding loops is fundamental because it allows handling repetitive tasks and performing calculations efficiently.
