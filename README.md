# CP-WORKSHOP

## BASICS
### [Binary Exponentiation](https://cp-algorithms.com/algebra/binary-exp.html)
### [Greatest Common Divisor](https://cp-algorithms.com/algebra/euclid-algorithm.html)
### [Nth Fibonacci Number](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)
### [Sieve of Eratosthenes](https://cp-algorithms.com/algebra/sieve-of-eratosthenes.html)
### [Integer Factorization](https://cp-algorithms.com/algebra/factorization.html)
### Modular Arithmetic
```cpp
// Addition
(a + b) % m = ((a % m) + (b % m)) % m

// Subraction
(a - b) % m = ((a % m) - (b % m)) % m

// Multiplication
(a * b) % m = ((a % m) * (b % m)) % m

// Division (We need to use Mod Inverse)
(a / b) % m != ((a % m) / (b % m)) % m
```
### Modular Inverse
```cpp
// Using Fermat's Little  theorem
// If m is prime
modInv(a, m) {
    return fastpow(a, m - 2, m);
    // pow(a, m - 2) % m
}
(a / b) % m = ((a % m) * modInv(b, m)) % m
```

## TOPICS
### Binary Search
* [Tutorial](https://www.topcoder.com/community/competitive-programming/tutorials/binary-search)
* [AGGRCOW](https://www.spoj.com/problems/AGGRCOW/)
* [SNAKEEAT](https://www.codechef.com/problems/SNAKEEAT)

### Divide and Conquer
* [Merge Sort](https://www.geeksforgeeks.org/merge-sort/)
* [Inversion Count](https://www.geeksforgeeks.org/counting-inversions/)
* [TASTYD](https://www.codechef.com/problems/TASTYD)

### Dynammic Programming
* [Top 20 must do DP problems on GFG](https://www.geeksforgeeks.org/top-20-dynamic-programming-interview-questions/)
* [AtCoder Educational DP contest](https://atcoder.jp/contests/dp/tasks)
* [EXPCAN](https://www.codechef.com/problems/EXPCAN)
* [Burst Balloons](https://leetcode.com/problems/burst-balloons/)

### Disjoint Set Union (DSU)
* [Tutorial](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/)
* [Implementation](https://github.com/yash0530/CP/blob/master/01%20DSA/001%20DSU.cpp)
* [DISHOWN](https://www.codechef.com/problems/DISHOWN)
* [ABC 120D](https://atcoder.jp/contests/abc120/tasks/abc120_d)

### Tries
* [Tutorial](https://www.hackerearth.com/practice/data-structures/advanced-data-structures/trie-keyword-tree/tutorial/)
* [Implementation](https://github.com/yash0530/CP/blob/master/01%20DSA/016%20Trie.cpp)
* [MAX-XOR](https://www.hackerrank.com/challenges/maximum-xor/problem)
* [ENGLISH](https://www.codechef.com/problems/ENGLISH)

### Square Root Decomposition

### Polynomial Multiplication using FFT
* [Tutorial](https://cp-algorithms.com/algebra/fft.html) (Don't worry too much about math behind it, learn how to use it)

## ADVANCED
### Segment Tree

### DP on Trees

### Biconnectivity

### LCA in LogN (Binary Lifting)