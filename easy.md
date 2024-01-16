# Problem 1

Write a function `generate_random_age()` that generates a random age between 18 and 65.

```
import random
def generate_random_age():
```
# Problem 2
Create a function `generate_random_name()` that generates a random name.

```
import random
def generate_random_name():
```

# Problem 3
Combine the previous functions to create a function `generate_random_person()` that generates a random person with age, first name, and last name.

```
def generate_random_person():
```

# Problem 4
Write a Python function that takes two lists, keys_list and values_list, and creates a dictionary from them. Provide an example of how this function can be used, including the input lists and the resulting dictionary.

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
Create a function `extract_json_data(json_data, key)` that reads data and return in list form.
```
def extract_json_data(json_data):
```

# Problem 9

Convert a list of dicts to a dict of lists

```
>>> list_to_dict(data: list)

data = [{"name": "a", "age": 21}, {"name": "b", "age": 43}]
output = {"name": ["a", "b"], "age": [21,43]}
```

# Problem 10
Convert a dict of lists to a list of dicts

```
>>> dict_to_list(data: dict)

data = {"name": ["a", "b"], "age": [21,43]}
output = [{"name": "a", "age": 21}, {"name": "b", "age": 43}]
```