## Variables 

```python
cls = "int"
cls2 = "Float"
cls3 = "str"

print(cls)
print(cls2)
print(cls3)

hello = "Hello World"
print(Hello)

var1 = 10

print(id(var))

var1 = 100
print(id(var1))
When var1 was reassigned from 10 to 100, Python created a new object in memory. Integers are immutable, so Python does not change the original object, it assigns a new memory location. The old memory address is no longer used.
```

```python
var2 = 100
print(id(var2))

var2 = 100
print(id(var2))
Python reused the same memory address for var2. This is because Python caches small integers, so when the same integer literal is used, the interpreter may reuse the existing object instead of creating a new one.
```

```python
str1 = "Hello"
str2 = "World"

print(hex(id(str1[0])), hex(id(str1[1])), hex(id(str1[2])), hex(id(str1[3])), hex(id(str1[4])))
print(hex(id(str2[0])), hex(id(str2[1])), hex(id(str2[2])), hex(id(str2[3])), hex(id(str2[4])))
```

## Challenges
Im having a bit of trouble wrapping my head aorund this one.
