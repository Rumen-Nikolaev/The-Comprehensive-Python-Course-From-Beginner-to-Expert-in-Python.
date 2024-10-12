# Control Flow in Python: `if`, `elif`, and `else` Statements

Control flow in Python allows you to execute certain blocks of code only when specific conditions are met. This is done using `if`, `elif`, and `else` statements. These conditional statements are used to control the flow of logic within a program.

## Syntax Overview

- **`if` statement**: Executes a block of code if the condition is `True`.
- **`elif` statement**: Allows you to check multiple conditions after the initial `if` statement.
- **`else` statement**: Executes a block of code if none of the previous conditions are met.

### Example 1: Basic `if` statement

```python
hungry = True

if hungry:
    print("FEED ME!")

