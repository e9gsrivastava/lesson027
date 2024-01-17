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
Implement a function max_profit(prices) to find the maximum profit from buying and selling a stock given an array of prices.

```
def max_profit(prices):
```

For example:
```
max_profit([7,1,5,3,6,4]) should return 5.
```

# Problem 4

The N-Queens puzzle is the problem of placing N chess queens on an N×N chessboard so that no two queens threaten each other. Write a function n_queens(n) to find one possible solution.

```
def n_queens(n):
```
# Problem 5
Implement a function is_palindrome(s) that checks whether a string is a palindrome, considering only alphanumeric characters and ignoring cases.
```
def is_palindrome(s):
```
For example:
```
is_palindrome("A man, a plan, a canal: Panama") should return True
```
# Problem 6-- Reciprocal cycles
You have N number of people and C number of chocolates. You need to distribute the chocolates among the people in such a way that each person at position P gets the maximum number of chocolates. However, no one should receive double or more chocolates than the persons on their left or right.
```
def distribute_chocolates(N, C, P):
```
For example:

```
distribute_chocolates(5, 15, 2) should return 5.
```
In this example, there are 5 people, 15 chocolates, and the person at position 2 should receive the maximum number of chocolates. The distribution should follow the given constraints.


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
