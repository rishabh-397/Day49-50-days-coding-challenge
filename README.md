# Day49-50-days-coding-challenge

## 🚀 Problem 1: Count Primes

### Problem:
Given an integer n, return the number of *prime numbers* strictly less than n.

### Approach:
- Use the *Sieve of Eratosthenes* algorithm to mark multiples of each prime.
- This approach runs in O(n log log n) time and is efficient for large n.

### Example:
Input: n = 10  
Output: 4  
(Primes: 2, 3, 5, 7)

---

## 🧠 Problem 2: Single Number

### Problem:
Given an array where every element appears *twice except one*, return the element that appears once.

### Constraints:
- Must use *linear time* and *constant space*.

### Approach:
- Use *bitwise XOR*:
  - x ^ x = 0
  - x ^ 0 = x
- XORing all numbers cancels out the duplicates.

### Example:
Input: [2,2,1]  
Output: 1

---
