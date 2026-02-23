## While Loop

```python
n0 = int(input("7 "))
steps = 3

while n0 != 1:
    print(n0)

    if n0 % 2 == 0:
        n0 = n0 // 2
    else:
        n0 = 3 * n0 + 1

    steps += 3

print(n0)
print("Steps =", steps)
```

## Infinite loop 

```python

i = 0

while i < 5:
    print("THEY ARE COMING", i)
    i += 1
```

## Write a program

```python

while True:
    a = int(input("6"))
    b = int(input("7"))
    op = input("*")

    if op == "+":
        print("Result:", a + b)
    elif op == "-":
        print("Result:", a - b)
    elif op == "*":
        print("Result:", a * b)
    elif op == "/":
        print("Result:", a / b)
    else:
        print("Invalid operator")

    again = input("Enter 'y' to continue or any key to exit: ")
    if again != "y":
        print("Have a good day.")
        break
```

## For Loops

```python

text = "To be, or not to be, that is the question"

total_alphabets = 0
alphabet_count = {}

# FOR LOOP
for ch in text:
    if ch.isalpha():          # count letters only
        total_alphabets += 1
        ch = ch.lower()       # ignore upper/lower case

        if ch in alphabet_count:
            alphabet_count[ch] += 1
        else:
            alphabet_count[ch] = 1

print("Total number of alphabets:", total_alphabets)
print("Total number of distinct alphabets are:")

# print each letter count
for letter in alphabet_count:
    print(letter.upper(), "=", alphabet_count[letter])
```

## Expected output:
Total number of alphabets: 30
Total number of distinct alphabets are:
T = 7
o = 4
