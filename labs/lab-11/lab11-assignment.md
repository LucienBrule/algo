# Lab 11

> NPC and Approximation

In this lab you are to find an APPROXIMATE but FAST solution to the following problem:

Input: a set S which has sets s(i) as its elements such that each s(i) includes some integers between 1 and n

Output: output minimum number of subset of elements of S that includes all the numbers between 1…n

---

Example: n=11
```
S={
    s(1)={1,3,5,7,10,11},
    s(2)={1,2,4,5,11},
    s(3)={4,8,9},
    s(4)={1,3,5,8,9,10},
    s(5)={2,6,10}
}
```
A solution for this example would be s(1), s(3), and s(5)

---

### Q1 Implement a polynomial time algorithm

### Q2: What is the time complexity of your algorithm

### Q3:How good is the solution found by your algorithm
> (i.e., is it optimum? If not what is the approximation ratio?)
> Hint: be greedy.
