# Python Sets Overview

A **set** in Python is an unordered collection of unique elements. This means that each element can only appear once within a set, and sets do not preserve the order of elements.

## Key Features

- **Unique Elements**: A set can only contain unique elements. If you try to add a duplicate, it will not be included again.
- **Unordered**: The elements in a set do not follow a specific order.
- **Mutable**: Sets can be modified by adding or removing elements.

## Syntax

You can create a set using the `set()` function or by using curly braces `{}`.

```python
# Creating an empty set
myset = set()

# Adding elements to a set
myset.add(1)
myset.add(2)

# Set now contains {1, 2}
