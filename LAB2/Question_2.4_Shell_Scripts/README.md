# Question 2.4 — Create Shell Scripts Using Variables and Loops (5 marks)

This directory contains three Bash scripts based on the exercise screenshot.

## Script 1: Variables and output
- Declares `STUDENT_NAME`, `COURSE`, and `SEM`
- Prints a formatted lab record header, values, and current date/time

Run:
```bash
chmod +x script1_hello.sh
./script1_hello.sh
```

## Script 2: Loops and conditionals
- For-loop counts from 1 to 5
- While-loop prints the first five powers of 2 (2^0 through 2^4)
- For-loop checks numbers 1–10 for even/odd and counts even numbers

Run:
```bash
chmod +x script2_loops.sh
./script2_loops.sh
```

Expected even-number count: **5**.

## Script 3: Function and command-line arguments
- Defines `is_prime()` to test primality
- With no arguments, tests integers 2 through 15
- With arguments, tests each provided number

Run:
```bash
chmod +x script3_functions.sh
./script3_functions.sh 7 11 15 23
./script3_functions.sh
```

For the argument run, 7, 11, and 23 are prime; 15 is not prime.

## Lab directory used in the question
The prompt suggests `cd ~/cse103_lab/LAB2/`. If you are working from a cloned repository, place these files in the corresponding LAB2 folder. All scripts use Bash.
