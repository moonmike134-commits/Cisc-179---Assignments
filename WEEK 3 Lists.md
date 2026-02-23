## Create a list of 100 integers

```python
numbers = list(range(1, 101))

print(numbers)
```

## Suppose that you have a list of 10 items long. How might you move the last three items from the end of the list to the beginning, keeping them in the same order?

```python
lst = [1,2,3,4,5,6,7,8,9,10]

lst = lst[-3:] + lst[:-3]

print(lst)
```

## Predict result
the answer would be 3

## Creat List / memory address

```python
# 1d - create a list and show memory addresses

# make a list with some duplicate numbers
my_list = [1, 2, 3, 3, 4, 5, 5, 6, 7, 8]

print("The list is:")
print(my_list)

print("Memory addresses of each item:")

# loop through the list
for x in my_list:
    print(id(x))
```

## 1g. Copy nested list WITHOUT affecting original
x = [[1,2,3],[4,5,6],[7,8,9]]

```python

import copy

y = copy .deepcopy(x)

```

## Multiple expressions in list comprehension
Yes

## Count spaces using list comprehension

```python

spaces = len([c for c intext if c == ""])
print(spaces)
```

## Use 5 List Operations

```python

# make a list
my_list = [1, 2, 3, 4, 5]

print(my_list)

# operation 1 - append
my_list.append(6)
print(my_list)

# operation 2 - insert
my_list.insert(0, 0)
print(my_list)

# operation 3 - remove
my_list.remove(3)
print(my_list)

# operation 4 - pop
my_list.pop()
print(my_list)

# operation 5 - sort
my_list.sort()
print(my_list)

```
