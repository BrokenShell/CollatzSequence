# Code Challenge: Collatz Sequence

The Collatz sequence is a sequence of numbers defined for a positive integer n. The sequence is defined as follows:

1. Start with an integer n > 0. 
2. If n is even, the next number is n / 2. 
3. If n is odd, the next number is 3n + 1. 
4. The sequence ends when it reaches 1. 

## Task:

Your task is to implement a Python function collatz_sequence(n) that generates the Collatz sequence for a given integer n. The function should return a list containing the sequence, including the starting number n and the final value 1.

### Examples:

```
>>> collatz_sequence(6)
[6, 3, 10, 5, 16, 8, 4, 2, 1]
```

```
>>> collatz_sequence(7)
[7, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1]
```

The primary challenge is to consider how to implement the sequence in Python and how to handle the different operations depending on whether the number is odd or even.

Bonus Challenge: Use no if statements in your implementation.
