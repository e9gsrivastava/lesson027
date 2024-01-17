# Problem 1

Write a function to sort a list of numbers without using sort method

```
import random
def sort(my_list):
```
# Problem 2
Create a function `generate_random_name()` that generates a random name.

```
import random
def generate_random_name():
```

# Problem 3
Create a Python function validate_email(email) that validates if a given string is a valid email address.
```
def validate_email(email):
```
```
validate_email("user@example.com")  # True
validate_email("invalid_email")      # False
validate_email("another@example")     # False
validate_email("test.email@domain")   # False
validate_email("valid.email@domain.com")  # True
```

# Problem 4
Write a Python function that takes two lists, keys_list and values_list, and creates a dictionary from them.

```
def lists_to_dict(keys, values):
```

```
keys_list = ["name", "age", "city"]
values_list = ["John", 25, "New York"]
```
# Problem 5
Implement a Python function named is_perfect_square that takes an integer as input and returns True if the number is a perfect square and False otherwise? A perfect square is a number that can be expressed as the product of an integer with itself. Provide an example by using the function to check if a specific number is a perfect square and include the result in your response.

```
def perfect_sq(num)
```
# Problem 6
Write a function `count_words_in_txt(text)` to find the number of words in the provided textfile.

```
def count_words_in_txt(text):
```
# Problem 7
Develop a function `average_column(csv_file, column_name)` that calculates the average value of a specific column in a CSV file.

```
def average_column(csv_file, column_name):
```

# Problem 8
Create a function calculate_factorial(n) that calculates the factorial of a given number using recursion.
```
def calculate_factorial(n):
```
# Problem 9

Convert a list of dicts to a dict of lists

```
>>> list_to_dict(data: list)

data = [{"name": "a", "age": 21}, {"name": "b", "age": 43}]
output = {"name": ["a", "b"], "age": [21,43]}
```

# Problem 10
Write a Python function capitalize_names(names) that takes a list of names as input and converts the first and last names to have their first letters capitalized.

```
def capitalize_names(names):
```
Example:
```
names_list = ["john doe", "jane smith", "bob johnson"]
result = capitalize_names(names_list)
# Output: ['John Doe', 'Jane Smith', 'Bob Johnson']
```
