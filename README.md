# 12.-Python-All-Variables-in-Python
Various types of variables are used in Python. This includes their purpose, usage, and code examples. The information is formatted in a table for clarity.
## Table: Python Variable Types and Their Uses

| **Variable Type**      | **Description**                                                                 | **Code Example**                                |
|-------------------------|---------------------------------------------------------------------------------|------------------------------------------------|
| **Integer (`int`)**     | Stores whole numbers, used in counting or discrete data.                       | `age = 25`                                     |
| **Float (`float`)**     | Stores decimal numbers, used for continuous data.                              | `height = 5.9`                                 |
| **String (`str`)**      | Stores sequences of characters, used for textual data.                         | `name = "Alice"`                               |
| **Boolean (`bool`)**    | Stores `True` or `False`, used in conditional logic.                           | `is_student = True`                            |
| **List (`list`)**       | Stores an ordered collection of items, used for grouping related data.         | `fruits = ["apple", "banana", "cherry"]`       |
| **Tuple (`tuple`)**     | Stores an ordered and immutable collection of items.                           | `coordinates = (10, 20)`                       |
| **Dictionary (`dict`)** | Stores key-value pairs, used for mapping or associative arrays.                | `student = {"name": "Bob", "age": 21}`         |
| **Set (`set`)**         | Stores an unordered collection of unique items.                                | `unique_numbers = {1, 2, 3}`                   |
| **Frozenset (`frozenset`)| Like a `set`, but immutable (cannot be modified).                              | `immutable_set = frozenset({1, 2, 3})`         |
| **Complex Number (`complex`)| Stores numbers with real and imaginary parts.                              | `z = 3 + 4j`                                   |
| **NoneType (`None`)**   | Represents the absence of a value.                                             | `x = None`                                     |


# Python Variables: Types and Uses

This document provides a comprehensive overview of all the variable types in Python, categorized with descriptions and examples.

---

## **1. Primitive Data Types**
These are the basic building blocks for data manipulation in Python.

| **Variable Type** | **Description**                                                                 | **Code Example**             |
|--------------------|---------------------------------------------------------------------------------|------------------------------|
| **Integer (`int`)** | Used for whole numbers.                                                        | `age = 25`                   |
| **Float (`float`)** | Used for decimal numbers.                                                      | `price = 19.99`              |
| **Complex (`complex`)** | Represents numbers with real and imaginary parts.                            | `z = 3 + 4j`                 |
| **String (`str`)** | Used to store text.                                                             | `name = "Alice"`             |
| **Boolean (`bool`)** | Represents `True` or `False`.                                                  | `is_active = True`           |
| **NoneType (`None`)** | Represents a null value.                                                      | `value = None`               |

---

## **2. Collection Data Types**
These are used to store multiple items in a single variable.

| **Variable Type**      | **Description**                                                                 | **Code Example**                     |
|-------------------------|---------------------------------------------------------------------------------|--------------------------------------|
| **List (`list`)**       | Ordered, mutable collection of items.                                           | `fruits = ["apple", "banana"]`       |
| **Tuple (`tuple`)**     | Ordered, immutable collection of items.                                         | `coordinates = (10, 20)`             |
| **Set (`set`)**         | Unordered collection of unique items.                                           | `unique_numbers = {1, 2, 3}`         |
| **Frozenset (`frozenset`)| Immutable version of a set.                                                     | `fs = frozenset({1, 2, 3})`          |
| **Dictionary (`dict`)** | Key-value pairs, unordered and mutable.                                         | `person = {"name": "Bob"}`           |

---

## **3. Specialized Data Types**
These are part of Python's standard library and are used in specific scenarios.

| **Variable Type**          | **Description**                                                                         | **Code Example**                      |
|-----------------------------|-----------------------------------------------------------------------------------------|---------------------------------------|
| **Range (`range`)**         | Represents a sequence of numbers.                                                       | `numbers = range(1, 10)`              |
| **Bytes (`bytes`)**         | Represents immutable byte sequences.                                                    | `data = b"hello"`                     |
| **Bytearray (`bytearray`)** | Mutable version of bytes.                                                               | `mutable_data = bytearray(b"hello")`  |
| **Memoryview (`memoryview`)** | Used to access the memory of an object.                                                 | `view = memoryview(b"hello")`         |

---

## **4. User-Defined Data Types**
These are created by the user using Python's features like classes.

| **Variable Type**      | **Description**                                             | **Code Example**                           |
|-------------------------|-----------------------------------------------------------|--------------------------------------------|
| **Class/Objects**       | Custom data types defined using the `class` keyword.       | `class Person: ...`                        |
| **Instance Variables**  | Variables unique to each instance of a class.              | `self.name = "Alice"`                      |
| **Static Variables**    | Shared variables across all instances of a class.          | `class_var = "Shared"`                     |

---

## **5. Advanced Data Types**
These include types used for advanced operations or libraries.

| **Variable Type**     | **Description**                                                                         | **Code Example**                                |
|------------------------|-----------------------------------------------------------------------------------------|------------------------------------------------|
| **Deque (`deque`)**    | Double-ended queue from the `collections` module.                                      | `from collections import deque`               |
| **NamedTuple**         | Immutable and named tuple from the `collections` module.                               | `from collections import namedtuple`          |
| **DefaultDict**        | Dictionary with default values.                                                        | `from collections import defaultdict`         |
| **Counter**            | A special type of dictionary for counting elements.                                    | `from collections import Counter`             |

---

## **6. Mutable vs Immutable Variables**
Python variables can be mutable (modifiable) or immutable (non-modifiable).

| **Type**        | **Examples**                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **Mutable**      | `list`, `dict`, `set`, `bytearray`                                          |
| **Immutable**    | `int`, `float`, `str`, `tuple`, `frozenset`, `bytes`, `NoneType`, `complex` |

---

## **Code Examples**

### **Primitive Data Types**
```python
age = 25  # int
price = 19.99  # float
z = 3 + 4j  # complex
name = "Alice"  # str
is_active = True  # bool
value = None  # NoneType
