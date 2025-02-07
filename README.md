# Cs50p Python lesson 1 Documentation

## Name Input and Greeting
This script demonstrates string manipulation and conditional statements:
```python
name = str(input("What is your name? "))
name = name.strip().title()
print(f"the name is: {name}")

if name.upper() == 'BRIAN':
    print("Hello,", name)
else:
    print("Hello")
```

Key features:
- Uses `strip()` to remove whitespace
- `title()` capitalizes first letter of each word
- Demonstrates string comparison with `upper()`
- Shows both f-string and comma-separated printing

## Addition Operations
This script shows different ways to perform addition and handle numeric input:
```python
x = 190
y = 40
print(int(x+y))

x = int(input('enter the value of x: '))
y = int(input('enter the value of y: '))

a = x + y
print(f'the value of addition is: {a}')

b = int(x + y)
print(f'the value of addition is: {b}')

c = int(x) + int(y)
print(f'the value of addition is: {b}')
```

Key features:
- Demonstrates variable assignment
- Shows different ways to handle integer addition
- Uses f-strings for output formatting
- Illustrates input conversion to integers

## Division and Rounding
This script demonstrates floating-point division and different ways to format decimal numbers:
```python
x = float(input("what is the value of x? "))
y = float(input("what is the value of x? "))

a = x / y
print(a)                # prints full floating-point number
print(round(a, 2))      # rounds to 2 decimal places
print(f"{a:.2f}")       # formats to 2 decimal places
```

Key features:
- Uses `float()` for decimal number input
- Shows three different ways to handle decimal output:
  - Direct printing of float
  - Using `round()` function
  - Using f-string formatting with precision specifier
