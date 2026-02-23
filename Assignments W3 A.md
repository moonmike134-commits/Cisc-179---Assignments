## 5. Problem solving

  ## Even / Odd
  
```python
num = int(input("Enter number: "))

if num & 1:
  print("Odd")
else: 
  print("Even")
```

## Code Revision

```python

name = input("What's your name?")
time = int(input("What time is it? "))

# Nested if-elif-else
if time < 1200:
  print("Hi " + name + ", good morning!")
elif time < 1800:
  print("Hi " + name + ", good afternoon!")
else:
  print("Hi " + name + ", good evening!")
print("Good Bye!")
```

## Output Prediction
one
two
x == y is True
y == int(z) is True
elif and else wont run anymore.


## Challenges
Understanding the bitwise operators was hard to work with using binary numbers, also making the truth table required a bit of research on the operators so i ended up looking for another guide to make it a bit easier for me.
