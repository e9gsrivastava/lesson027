# Problem 1 
Given strings s and t, return the number of distinct subsequences of t in s.

Explanation:
This problem involves counting the number of distinct ways to form the target string t from the source string s by deleting some characters. The order of characters in t must be maintained.

Example:

```
Input: s = "rabbbit", t = "rabbit"
Output: 3
```
In the example, there are three distinct subsequences of "rabbit" in "rabbbit":

"rabbbit" (delete the first 'b' and the second 'b')
"rabbit" (delete the second 'b')
"rabbit" (delete the second 'b' and the third 'b')
The goal is to count the number of distinct ways to obtain the target string "rabbit" from the source string "rabbbit."

```
def count_distinct_subsequences(s, t):
```
# Problem 2

Given an integer array nums, return the number of smaller elements to the right of each element.

Explanation:
For each element in the array nums, we need to count the number of elements to its right that are smaller than it. This problem often involves using efficient data structures to perform the counting.

```
Input: [5, 2, 6, 1]
Output: [2, 1, 1, 0]
```
In the example, for the element 5, there are two elements (2 and 1) to its right that are smaller. For the element 2, there is one element (1) to its right that is smaller. For the element 6, there is one element (1) to its right that is smaller. For the element 1, there are no elements to its right that are smaller.

The goal is to return a list where each element indicates the count of smaller numbers to the right of the corresponding element in the input array.

```
def count_smaller_numbers_to_right(nums):
```


# Problem 3
You are given the following information, but you may not use any libraries:

1 Jan 1900 was a Monday.
Thirty days have September, April, June, and November.
All the rest have thirty-one, saving February alone, which has twenty-eight, rain or shine.
On leap years, twenty-nine.
A leap year occurs on any year evenly divisible by 4, but not on a century unless it is divisible by 400.
How many Sundays fell on the first of the month during the twentieth century (1 Jan 1901 to 31 Dec 2000)?

```
def counting_sundays():
```


# Problem 4

The N-Queens puzzle is the problem of placing N chess queens on an N×N chessboard so that no two queens threaten each other. Write a function n_queens(n) to find one possible solution.

```
def n_queens(n):
```
# Problem 5

In a M X N grid, find the greatest product of four adjacent numbers in the same direction (up, down, left, right, or diagonally). Write a function largest_product_in_series(series).

```
def largest_product_in_series(series):
```

# Problem 6
A unit fraction contains 1 in the numerator. The decimal representation of the unit fractions with denominators 2 to 10 are given:
```
1/2 = 0.5
1/3 = 0.(3)
1/4 = 0.25
1/5 = 0.2
1/6 = 0.1(6)
1/7 = 0.(142857)
1/8 = 0.125
1/9 = 0.(1)
1/10 = 0.1
```
Where 0.1(6) means 0.166666..., and has a 1-digit recurring cycle. It can be seen that 1/7 has a 6-digit recurring cycle.

Write a function reciprocal_cycle_length(d) that returns the length of the recurring cycle in the decimal fraction 1/d for a given denominator d.

```
def reciprocal_cycle_length(d):
```
For example, reciprocal_cycle_length(7) should return 6 as the recurring cycle in the decimal fraction 1/7 is 6 digits long.

# Problem 7 
Write a Python function, number_to_words(n), that converts a given integer n (where 0 <= n <= 9999) into words. The function should return the English words representing the given number.

```
def number_to_words(n):
```
For example:
```
number_to_words(123) should return 'one hundred twenty-three'.
```
```
number_to_words(4500) should return 'four thousand five hundred'.
```

# Problem 8 

You are given an array of integers. Your task is to determine whether the array can be almost sorted by performing at most one operation of swapping or reversing. If the array can be almost sorted, print "yes" along with the type of operation. If it is not possible, print "no".

Write a function almost_sorted(arr) that takes an array of integers as input and returns a string indicating whether the array can be almost sorted.

```
def almost_sorted(arr):
```
For example:

```
almost_sorted([1, 5, 3, 4, 2]) should return "yes reverse 2 5".
```
```
almost_sorted([1, 2, 4, 3, 5]) should return "yes swap 3 4".
```


# probelem 9
Write a function infix_to_postfix(infix_expression) that converts an infix arithmetic expression to postfix notation. The infix expression will consist of integers and the operators '+', '-', '*', and '/'. Assume that the input expression is well-formed.

```
def infix_to_postfix(infix_expression):
```
```
infix_to_postfix("3 + 5 * ( 2 - 8 ) / 4") should return
 "3 5 2 8 - * 4 / +".
```

# problem 10


Write a function time_in_words(h, m) that converts the given time represented by hours (h) and minutes (m) into words. The function should return a string representing the time in words.

```
def time_in_words(h, m):
```

For example:

```
time_in_words(5, 0) should return "five o' clock".
```
```
time_in_words(5, 15) should return "quarter past five".
```
