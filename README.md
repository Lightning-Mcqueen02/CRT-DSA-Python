# CRT Training – DSA with Python

This repository contains my daily learning notes and coding solutions from CRT (Campus Recruitment Training). I am learning Data Structures and Algorithms (DSA) using Python 3 and practising problems from LeetCode, GeeksforGeeks, and Codeforces.

## Table of Contents

- [Day 1 – Python Basics and Number Problems](#day-1--python-basics-and-number-problems)
- [Day 2 – Loops and Digit Problems](#day-2--loops-and-digit-problems)
- [Day 3 – Arrays, Strings and Patterns](#day-3--arrays-strings-and-patterns)
- [Day 4 – Array Problems](#day-4--array-problems)
- [Day 5 – Sliding Window Problems](#day-5--sliding-window-problems)

## Day 1 – Python Basics and Number Problems

<details>
<summary>Click to view Day 1 concepts and code</summary>

### 1. Even or Odd Number

**Concept:** Use the modulus operator `%` to check whether a number is divisible by 2.

**Key Points:**
- `n % 2 == 0` means the number is even.
- Otherwise, the number is odd.

**Code:**
```python
n = int(input())

if n % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### 2. Prime Number

**Concept:** A prime number is greater than 1 and has exactly two factors: 1 and itself.

**Key Points:**
- Numbers less than or equal to 1 are not prime.
- Check whether any number from 2 to `n - 1` divides `n`.

**Code:**
```python
n = int(input())

if n <= 1:
    print("Not Prime")
else:
    prime = True

    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

    if prime:
        print("Prime")
    else:
        print("Not Prime")
```

### 3. Convert Seconds into Hours, Minutes and Seconds

**Concept:** Use integer division `//` and modulus `%` to convert seconds.

**Key Points:**
- `//` gives the whole-number quotient.
- `%` gives the remainder.
- One hour has 3600 seconds, and one minute has 60 seconds.

### 4. Leap Year

**Concept:** Check divisibility by 400, 100 and 4 in the correct order.

### 5. Odd Divisors or Not

**Concept:** Repeatedly divide the number by 2. If the remaining number is greater than 1, it has an odd divisor greater than 1.

**Platform:** Codeforces 1475A

### 6. Cheap Travel

**Concept:** Compare the cost of buying individual tickets with the cost of buying combined tickets.

**Platform:** Codeforces 466A

</details>

## Day 2 – Loops and Digit Problems

<details>
<summary>Click to view Day 2 concepts and code</summary>

### 1. New Year and Hurry

**Concept:** Calculate the time remaining and count how many problems can be solved within that time.

**Platform:** Codeforces 750A

### 2. Sum of Digits

**Concept:** Extract each digit using `% 10` and remove the last digit using `// 10`.

### 3. Count Digits

**Concept:** Repeatedly divide a number by 10 and count how many times the loop runs. Handle zero separately.

### 4. Reverse an Integer

**Concept:** Extract digits and build the reversed number using `rev = rev * 10 + digit`.

**Platform:** LeetCode 7

</details>

## Day 3 – Arrays, Strings and Patterns

<details>
<summary>Click to view Day 3 concepts and code</summary>

### 1. Top K Frequent Elements
**Concept:** Use a dictionary to count frequencies and sort elements by their frequency.

### 2. Contains Duplicate
**Concept:** Compare the length of a list with the length of its set.

### 3. Valid Anagram
**Concept:** Two strings are anagrams if they contain the same characters with the same frequencies. Sorting both strings is one simple approach.

### 4. Rotate Array
**Concept:** Move the last `k` elements to the front to rotate the array right.

### 5. Pattern Printing
**Concept:** Use nested loops to print left-aligned triangles, right-aligned triangles, hollow squares and pyramids.

</details>

## Day 4 – Array Problems

<details>
<summary>Click to view Day 4 concepts and code</summary>

### 1. Two Sum
**Concept:** Use a dictionary to find the complement of each number and return the two indices.

### 2. Largest Element
**Concept:** Assume the first element is the largest, then compare every element.

### 3. Rotate Array by One
**Concept:** Remove the last element and insert it at the beginning.

### 4. Minimum and Maximum
**Concept:** Track the smallest and largest values while traversing the array.

### 5. Sum of Array
**Concept:** Add each element to a running total.

### 6. Alternating Elements
**Concept:** Visit indices `0, 2, 4, ...` to collect alternate elements.

### 7. Replace Zeros with Fives
**Concept:** Convert the number to a string, replace `0` with `5`, and convert it back to an integer.

### 8. Palindrome Array
**Concept:** Compare the array with its reverse.

### 9. Sort Colors
**Concept:** Sort an array containing only `0`, `1` and `2`, using frequency counting or the Dutch National Flag algorithm.

### 10. Move Zeroes
**Concept:** Keep nonzero elements in their original order and move zeroes to the end.

### 11. Array with All Palindromes
**Concept:** Convert each number to a string and check whether it reads the same backward.

### 12. Reverse Array in Groups
**Concept:** Reverse each group of `k` elements separately.

</details>

## Day 5 – Sliding Window Problems

<details>
<summary>Click to view Day 5 concepts and code</summary>

### 1. Maximum Sum Subarray of Size K
**Concept:** Find the largest sum among all contiguous subarrays of length `k`.

### 2. Maximum Consecutive Ones
**Concept:** Count consecutive ones and reset the count when a zero appears.

### 3. Maximum Average Subarray I
**Concept:** Find the maximum sum of a subarray of length `k`, then divide it by `k`.

### 4. Count Subarrays by Threshold
**Concept:** Count subarrays of length `k` whose average is at least the given threshold.

### 5. Substrings of Size Three with Distinct Characters
**Concept:** Check each substring of length three and count it if all three characters are different.

**Platform:** LeetCode 1876

### 6. Maximum Points from Cards
**Concept:** Find the maximum score by choosing `k` cards from the beginning or end of the array.

### 7. Longest Substring Without Repeating Characters
**Concept:** Use a sliding window and a set to find the longest substring containing no repeated characters.

</details>

## Languages and Platforms

- **Language:** Python 3
- **Platforms:** LeetCode, GeeksforGeeks and Codeforces

## Goals

- Improve logical thinking and problem-solving skills.
- Understand DSA concepts from the basics.
- Practise coding problems regularly.
- Prepare for coding assessments and placement interviews.

This repository will be updated regularly as I continue my CRT training.
