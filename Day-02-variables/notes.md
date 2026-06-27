# Day 2 – Variables in Python 🐍

## Definition

A variable is a name used to store data in memory. It acts like a labeled container that holds a value.

### Syntax

```python
variable_name = value
```

### Example

```python
name = "Varsha"
age = 20
height = 5.3
```

## Why Variables?

* Store data for later use.
* Avoid repeating values.
* Make code easier to update and understand.

## Variable Naming Rules

* Can contain letters, numbers, and underscores.
* Cannot start with a number.
* Cannot contain spaces.
* Cannot use Python keywords.

### Valid

```python
student_name = "Varsha"
marks123 = 95
```

### Invalid

```python
1name = "Varsha"
student-name = "Anu"
class = 10
```

## Multiple Assignment

Different values:

```python
name, age, city = "Varsha", 20, "Puducherry"
```

Same value:

```python
x = y = z = 100
```

## Dynamic Typing

Python allows changing the data type of a variable.

```python
x = 10
x = "Hello"
```

## Useful Function

```python
type(variable_name)
```

Returns the data type of the variable.

## Real-Life Examples

### Student

```python
student_name = "Varsha"
department = "AI & DS"
year = 3
```

### Shopping

```python
price = 50
quantity = 2
total = price * quantity
```

## Common Mistakes

❌ Missing quotes for strings

```python
name = Varsha
```

✅ Correct

```python
name = "Varsha"
```

❌ Using spaces

```python
student name = "Varsha"
```

✅ Correct

```python
student_name = "Varsha"
```

## Revision

* Variable = Container for storing data.
* Syntax: `variable_name = value`
* Variables can change values.
* Use meaningful names.
* Python supports dynamic typing.
