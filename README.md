# Day-118-Pop-By-Index
# Python Day 118 - Pop By Index

## Description

This program demonstrates how to use the `pop()` method to remove an element from a specific index in a Python list.

## Example

```text
Original list: [10, 20, 30, 40, 50]
Removed element: 30
Updated list: [10, 20, 40, 50]
```

## Code

```python
numbers = [10, 20, 30, 40, 50]

print("Original list:", numbers)

removed_number = numbers.pop(2)

print("Removed element:", removed_number)
print("Updated list:", numbers)
```

## Concepts Used

* Lists
* Indexing
* `pop()` method
* Variables
* `print()`

## How It Works

1. A list named `numbers` is created.
2. `pop(2)` is used to remove the element at index 2.
3. Indexing in Python starts from 0.
4. The removed element is stored in `removed_number`.
5. The removed element and updated list are displayed.

## Important Note

```python
numbers.pop(2)
```

Here, `2` is the index, not the value.

For example:

```text
[10, 20, 30, 40, 50]
          ↑
       index 2
```

Therefore, `30` is removed.

## File Name

`pop_by_index.py`

## Goal

The goal of this program is to understand how to remove an element from a specific index using the `pop()` method.
