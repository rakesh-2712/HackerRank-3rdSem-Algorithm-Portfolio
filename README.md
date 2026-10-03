# HackerRank Algorithms & GitHub Coding Portfolio

## Student Details

| Field                  | Details                                                              |
| ---------------------- | -------------------------------------------------------------------- |
| **Name**               | M Rakesh Kumar                                                       |
| **SRN**                | R25EF129                                                             |
| **Semester**           | 3rd Semester                                                         |
| **HackerRank Profile** | https://www.hackerrank.com/profile/rakeshmeti_2005                   |
| **GitHub Repository**  | https://github.com/rakesh-2712/HackerRank-3rdSem-Algorithm-Portfolio |

---

## Introduction

This repository contains my solutions for the **HackerRank Algorithms & GitHub Coding Portfolio** activity. The objective of this activity is to strengthen problem-solving skills, understand algorithmic techniques, analyze time and space complexity, and maintain coding solutions using Git and GitHub.

The five mandatory problems cover array processing, searching, sorting, and greedy techniques. All solutions in this repository are implemented in **C** and organized into separate folders for clarity.

---

## Problems Solved

| # | Problem                 | Technique                  | Time Complexity | Space Complexity |
| - | ----------------------- | -------------------------- | --------------- | ---------------- |
| 1 | Mini-Max Sum            | Single-pass traversal      | O(N)            | O(1)             |
| 2 | Birthday Cake Candles   | Maximum + frequency count  | O(N)            | O(1)             |
| 3 | Insertion Sort – Part 1 | Insertion sort shifting    | O(N)            | O(1)             |
| 4 | Binary Search           | Divide and conquer         | O(log N)        | O(1)             |
| 5 | Mark and Toys           | Sorting + greedy selection | O(N log N)      | O(1) auxiliary   |

---

# 1. Mini-Max Sum

### Problem

Given five positive integers, calculate the minimum and maximum sums that can be obtained by summing exactly four of the five integers.

### Approach

The solution calculates the total sum of all elements while simultaneously finding the minimum and maximum values.

* Minimum sum = total sum − maximum element
* Maximum sum = total sum − minimum element

This avoids repeatedly calculating four-element sums.

### Complexity

* **Time:** O(N)
* **Space:** O(1)

### HackerRank Challenge

https://www.hackerrank.com/challenges/mini-max-sum/problem

### Solution

`01-Mini-Max-Sum/solution.c`

---

# 2. Birthday Cake Candles

### Problem

Given the heights of candles, determine how many candles have the maximum height.

### Approach

The algorithm maintains:

* `max` — the largest candle height found so far
* `count` — the number of candles having that height

When a larger value is found, the maximum and count are updated. When an equal maximum is found, the count is increased.

### Complexity

* **Time:** O(N)
* **Space:** O(1)

### HackerRank Challenge

https://www.hackerrank.com/challenges/birthday-cake-candles/problem

### Solution

`02-Birthday-Cake-Candles/solution.c`

---

# 3. Insertion Sort – Part 1

### Problem

Insert the last element of an array into its correct position in an already sorted portion of the array while printing every intermediate state.

### Approach

The last element is stored as the value to be inserted.

Starting from the element immediately before it:

1. Compare each element with the value.
2. Shift larger elements one position to the right.
3. Print the array after every shift.
4. Insert the stored value into its correct position.
5. Print the final array.

### Complexity

* **Time:** O(N)
* **Space:** O(1)

### HackerRank Challenge

https://www.hackerran
