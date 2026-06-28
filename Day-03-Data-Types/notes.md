# Day 3 – Data Types in Python 🐍

## Definition

A data type tells Python what kind of value a variable stores. It determines how the value is stored, used, and what operations can be performed on it.

## Relationship Between Variables and Data Types

* Variable → Container
* Value → Data stored in the container
* Data Type → Type of the stored value

Example:

```python
name = "Varsha"
```

* Variable: `name`
* Value: `"Varsha"`
* Data Type: `str`

## Main Data Types

| Data Type | Description        | Example  |
| --------- | ------------------ | -------- |
| int       | Whole numbers      | 20       |
| float     | Decimal numbers    | 8.92     |
| str       | Text inside quotes | "Varsha" |
| bool      | True or False      | True     |

## Checking Data Type

```python
print(type(variable_name))
```

## Difference

```python
age = 20      # int
cgpa = 8.75   # float
name = "Varsha"  # str
student = True   # bool
```

## Important Notes

* Integers are whole numbers.
* Floats contain decimal values.
* Strings must be inside quotes.
* Boolean values are always `True` or `False`.
* Python is case-sensitive.

## Common Mistakes

❌ `age = "20"` → String, not Integer.

❌ `student = true`

✅ `student = True`

❌ `price = 200` is an Integer.

✅ `price = 200.0` is a Float.

## Quick Revision

* `int` → Whole numbers
* `float` → Decimal numbers
* `str` → Text
* `bool` → True / False
* `type()` → Returns the data type of a variable
