# Activities

## Task 1

- Refer to the following link. Discuss how the
  Recursive Factorial works:
  https://www.cs.usfca.edu/~galles/visualization/RecFact.html
- Refer to the following link. Discuss how the Recursive Fibonacci works:
  https://www.cs.usfca.edu/~galles/visualization/DPFib.html

## Task 2

There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs at a time. There is a simple implementations in `./src/` folder. Discuss how the code works.

## Task 3

- There are `n` stairs, a person standing at the bottom wants to reach the top. The person can climb either 1 stair or 2 stairs or **3 stairs** at a time. Write a program that counts the number of ways, the person can reach the top. You can use the following program as a starter `./src/staircase1.cpp`. Also the link below might useful:
  https://www.includehelp.com/cpp-programs/stair-case-program-to-solve-the-staircase-problem.aspx

## Task 4: Individual (at home)

- What are the pros/cons of recursive over iterative Programming?
Recursive programs provide compact and clean code. A recursive program is a simple way of writing programs. There are some inherent problems like factorial, Fibonacci sequence, towers of Hanoi, tree traversals, etc. which require recursion for solving.

In other words, they are solved efficiently with recursion. They can also be solved with iterative programming using stacks or other data structures but there are chances to become more complex to implement.

Problem-solving powers of recursive as well as iterative programming are the same. However, recursive programs take more memory space as all the function calls need to be stored on the stack until the base case is matched.

Recursive functions also have a time overhead because of too many function calls and return values.
- Difference between recursion and induction.
# Recursion:
the process in which a function is called again and again until some base condition is met.
It is the way of defining in a repetitive manner. 
It starts from nth term till the base case. It has two components: Base condition and Recursive step.
We backtrack at each step to replace the previous values with the answers using the function. 
No assumptions are made .
Recursive function is always called to find successive terms.
It can lead to infinity if no base condition is given.

# Induction: 
Induction is the way of proving a mathematical statement.
It is the way of proving.
It starts from the initial till(n+1)th term.
It has two steps: 
Base Step and Inductive step

We just prove that the statement is true for n=1. Then we assume that n=k is true. Then we prove for n = k + 1.
The assumption is made for n=k
Here statements or theorems are proved and no terms are found.
There is no concept of infinity.



> Refer to the [links](#links) section below.

## Links

- https://cpp.sh/
- [Difference Between Recursion and Induction](https://www.geeksforgeeks.org/difference-between-recursion-and-induction/)
- [Recursion vs Iterative Programming](https://www.softwaretestinghelp.com/recursion-in-cpp/)
