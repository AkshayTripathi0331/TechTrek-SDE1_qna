# Dynamic Programming

## Introduction

Dynamic programming is a method for solving complex problems by breaking them down into simpler subproblems and solving each subproblem only once. It is typically used for optimization problems where the solution can be expressed recursively in terms of solutions to smaller subproblems.

## Key Concepts

- **Optimal Substructure**: A problem exhibits optimal substructure if an optimal solution to the problem contains optimal solutions to its subproblems.
  
- **Overlapping Subproblems**: Subproblems that recur repeatedly in a recursive solution.

- **Memoization**: Technique for storing the results of expensive function calls and reusing them when the same inputs occur again.

## Common Dynamic Programming Techniques

### 1. Top-Down (Memoization)

In this approach, the problem is solved recursively, and the results of subproblems are stored in a data structure (such as an array or a hash table) to avoid redundant computations.

### 2. Bottom-Up (Tabulation)

In this approach, the problem is solved iteratively by filling up a table with solutions to subproblems in a bottom-up manner.

## Common Interview Questions

### 1. Fibonacci Sequence

**Description:**
Calculate the nth Fibonacci number using dynamic programming.

**Solution:**
- Top-Down Approach (Memoization)
- Bottom-Up Approach (Tabulation)

### 2. Longest Common Subsequence

**Description:**
Find the longest subsequence common to two sequences.

**Solution:**
- Dynamic Programming Approach

### 3. Knapsack Problem

**Description:**
Given a set of items, each with a weight and a value, determine the maximum value that can be obtained by selecting a subset of items that fit into a knapsack of limited capacity.

**Solution:**
- Dynamic Programming Approach (0/1 Knapsack)
- Dynamic Programming Approach (Unbounded Knapsack)

## Additional Resources

- [GeeksforGeeks - Dynamic Programming](https://www.geeksforgeeks.org/dynamic-programming/)
- [TopCoder - Dynamic Programming Tutorial](https://www.topcoder.com/thrive/articles/Dynamic%20Programming:%20From%20Novice%20to%20Advanced)
- [LeetCode - Dynamic Programming Problems](https://leetcode.com/tag/dynamic-programming/)

## Conclusion

Dynamic programming is a powerful technique for solving optimization problems efficiently by breaking them down into smaller subproblems. By understanding key concepts such as optimal substructure, overlapping subproblems, and memoization/tabulation, and practicing with common dynamic programming problems, software engineers can enhance their problem-solving skills and excel in technical interviews.

---

Feel free to customize and expand upon each section with additional explanations, examples, and interview questions based on your preferences. The `Dynamic_Programming.md` file can serve as a comprehensive resource for SDE1 candidates preparing for dynamic programming-related interviews.