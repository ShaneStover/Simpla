# Simpla Syntax Documentation

## Variable Assignment
Variables can be assigned using the `=` sign:

num = 10
isTrue = true
name = "Simpla"

# Data Types
Simpla supports the following data types:

Numeric: Integer and floating-point numbers
Logical: true or false
Text: String values enclosed in quotes " " or ' '

```simpla
Copy code
num = 10       # Numeric
isTrue = true   # Logical
name = "Simpla" # Text
```

# Mathematical Operations
You can perform basic arithmetic operations such as addition, subtraction, multiplication, and division:

```simpla
sum = 5 + 3     # Addition
diff = 5 - 3    # Subtraction
prod = 5 * 3    # Multiplication
quotient = 5 / 3 # Division
```

# Logical Operations
Logical operations such as AND, OR, and NOT can be used:

```simpla
result = true AND false  # Logical AND
negation = NOT true      # Logical NOT
```
# If-Else Statement
Simpla supports conditional statements using if, else, and elif (optional):

```simpla
if num > 5:
    print("Greater than 5")
else:
    print("Less than or equal to 5")
```
# Input and Output
You can print values to the console using print and read input with read:

```simpla
print("Hello, world!")  # Prints text
name = read("Enter your name: ")  # Reads user input
```
# Declaring Structures
Structures can be created using the struct keyword. They allow you to group related data:

```simpla
struct Person:
    name = ""
    age = 0

john = Person()        # Create instance of Person
john.name = "John"     # Access and set field 'name'
john.age = 30          # Access and set field 'age'
```
# Accessing Structure Fields
You can access structure fields using the . operator:

```simpla

print(john.name)  # Output: John
