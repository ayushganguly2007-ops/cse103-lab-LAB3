# Lab Record — Question 2.4

## Aim
To write and execute Bash scripts using variables, conditional statements, for-loops, while-loops, functions, and command-line arguments.

## Script 1 — Variables and Output
Variables used:
- `STUDENT_NAME="Alice"`
- `COURSE="CSE103"`
- `SEM=2`

### Expected output (date/time varies)
```text
==============================================
 K.R. Mangalam University — Lab Record
==============================================
Student: Alice
Course: CSE103
Semester: 2
==============================================
Executed at: [current date and time]
```

## Script 2 — Loops and Conditionals
### Expected output
```text
--- For Loop: Counting 1 to 5 ---
Iteration: 1
Iteration: 2
Iteration: 3
Iteration: 4
Iteration: 5

--- While Loop: Powers of 2 ---
2^0 = 1
2^1 = 2
2^2 = 4
2^3 = 8
2^4 = 16

--- Even / Odd check for 1 to 10 ---
1 is ODD
2 is EVEN
3 is ODD
4 is EVEN
5 is ODD
6 is EVEN
7 is ODD
8 is EVEN
9 is ODD
10 is EVEN
Even numbers appeared: 5
```

**Answer:** 5 even numbers appear (2, 4, 6, 8, and 10).

## Script 3 — Functions and Arguments
### With arguments: `./script3_functions.sh 7 11 15 23`
```text
Checking command-line arguments:
7 is PRIME
11 is PRIME
15 is NOT prime
23 is PRIME
```

### Without arguments: `./script3_functions.sh`
The script tests all numbers from 2 to 15. Prime numbers in this range are **2, 3, 5, 7, 11, and 13**.

## Result
The three Bash scripts demonstrate variable assignment and output, iteration with for/while loops, if/else conditions, function definition, and command-line argument handling. The even-number count from 1 to 10 is 5.
