#  Python Lists

## What Is a List?

A **list** in Python is a built-in data structure that allows us to store multiple items in a single variable.

Instead of creating separate variables for every value, we can collect them all inside one list.

A list can store different types of data, such as:
- Integers
- Strings
- Floats
- Booleans
- Even other lists!

### Example

```python
my_list = [10, "Python", 3.14, True]
```

Here, we have stored four different values inside a single variable called `my_list`.

## 🔄 Lists Are Mutable

One of the most important features of Python lists is that they are **mutable**.

This means we can change a list after creating it. We can add new items, insert items at specific positions, or remove existing items without creating a completely new list.

### 1. Append

The `append()` method adds a new item to the end of a list.

```python
numbers = [1, 2, 3]

numbers.append(4)

print(numbers)
# Output: [1, 2, 3, 4]
```

### 2. Insert

The `insert()` method adds a new item at a specific position.

```python
numbers = [1, 2, 3]

numbers.insert(1, 10)

print(numbers)
# Output: [1, 10, 2, 3]
```

The first argument specifies the index, and the second argument is the value we want to insert.

### 3. Remove

The `remove()` method removes the first occurrence of a specific value from a list.

```python
numbers = [1, 2, 3, 4]

numbers.remove(3)

print(numbers)
# Output: [1, 2, 4]
```

**Note:** If the specified value does not exist in the list, Python raises a `ValueError`.

## 💡 Key Takeaway

Python lists make it easy to organize and manage multiple values in one place.

Their most important feature is mutability, which allows us to modify their contents whenever we need to.

> A list is not just a container for storing data; it is a flexible data structure that we can continuously update and modify.

---

**Keep Learning. Keep Experimenting.**
