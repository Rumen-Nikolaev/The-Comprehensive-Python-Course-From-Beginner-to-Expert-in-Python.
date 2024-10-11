# String Formatting in Python

String formatting allows you to easily inject variables into strings, avoiding repetitive concatenation. This process is known as **string interpolation**. In Python, there are two popular methods for string formatting:

## 1. `.format()` Method

This is an older method of string interpolation that uses curly braces `{}` as placeholders for variables. The variables are passed to the `.format()` method, which inserts them into the string.

### Basic Syntax:
```python
# Simple string insertion
print("This is a {}.".format("string"))

# Output: This is a string.
