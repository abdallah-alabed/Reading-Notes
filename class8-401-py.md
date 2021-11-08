# List Comprehensions in Python
form of filters, which allows for more precision in the way lists are handled.

**why comprehension methods**:
- List comprehension methods are an elegant way to create and manage lists. 
- list comprehensions are a more compact way of creating lists. 
- More flexible than for loops, list comprehension is usually faster than other methods.

## creating lists:
digits = [x for x in range(10)]

## replacing loops:
squares = [x**2 for x in range(10)]

print(squares)

## Multiplying Parts of a List
even_numbers = [ x for x in range(1,20) if x % 2 == 0]

## Lower/Upper case converter 
lower_case = [ letter.lower() for letter in ['A','B','C'] ]

upper_case = [ letter.upper() for letter in ['a','b','c'] ]

## Print numbers only from a given string
user_data = "Elvis Presley 987-654-3210"

phone_number = [ x for x in user_data if x.isdigit()]
