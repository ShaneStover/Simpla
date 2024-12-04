# Simpla Syntax Documentation

## Variable Assignment
Variables can be assigned using the `=` sign:
```simpla
var num = 10
var isTrue = true
var name = "Simpla"
```

# Data Types
Simpla supports the following data types:

Numeric: Integer and floating-point numbers
Logical: true or false
Text: String values enclosed in quotes " " or ' '

```simpla
Copy code
var num = 10       # Numeric
var isTrue = true   # Logical
var name = "Simpla" # Text
```

# Mathematical Operations
You can perform basic arithmetic operations such as addition, subtraction, multiplication, and division:

```simpla
var sum = 5 + 3     # Addition
var diff = 5 - 3    # Subtraction
var prod = 5 * 3    # Multiplication
var quotient = 5 / 3 # Division
```

# Logical Operations
Logical operations such as AND, OR, and NOT can be used:

```simpla
var result = true AND false  # Logical AND
var negation = NOT true      # Logical NOT
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
You can print values to the console using print and read input with read also using variables:

```simpla
var X = "Hello, World"
print(var(X))
print("Hello, world!")  # Prints text
var name = read("Enter your name: ")  # Reads user input and stores in variable
```
# Declaring Structures
Structures can be created using the struct keyword. They allow you to group related data:

```simpla
struct Person:
    var name = ""
    var age = 0

var john = Person()        # Create instance of Person
var john.name = "John"     # Access and set field 'name'
var john.age = 30          # Access and set field 'age'
```
# Accessing Structure Fields
You can access structure fields using the . operator:

```simpla

print(var(john.name))  # Output: John
