# 🐍 Python Dictionaries

## What Is a Dictionary?

A **dictionary** in Python is a data structure that allows us to store related information using **key-value pairs**.

You can think of a dictionary as a list, but with a different way of accessing data.

In a list, every item has an index (0, 1, 2, ...).

But in a dictionary, instead of using indexes, we use **keys** to find the information we need.

Think about a phone book:

- A person's name is the key.
- Their phone number is the value.

If you want to find someone's phone number, you don't need to remember their position in the phone book. You just search for their name!

### Example

```python
person = {
    "name": "Alex",
    "age": 25,
    "phone": "123456789"
}
```

Here:
- `"name"`, `"age"`, and `"phone"` are keys.
- `"Alex"`, `25`, and `"123456789"` are values.

## 🔍 How to Access Data?

To get a specific value, we use its key.

```python
print(person["name"])
# Output: Alex

print(person["age"])
# Output: 25
```

We don't need to know the position of the information. We just need its key!

## 🆚 List vs Dictionary

Imagine you want to store information about a car.

### Using a List

```python
car = ["Toyota", "Corolla", 2022]
```

To access the car's brand, you need to remember its index:

```python
print(car[0])
# Output: Toyota
```

### Using a Dictionary

```python
car = {
    "brand": "Toyota",
    "model": "Corolla",
    "year": 2022
}
```

Now you can access information using meaningful keys:

```python
print(car["brand"])
# Output: Toyota
```

This makes the code easier to understand because you can see exactly what information you're requesting.

## 💡 Key Takeaway

A Python dictionary is useful when you want to connect specific pieces of information.

For example:
- A person's name and phone number.
- A car's brand and license plate.
- A student's name and grade.
- A product's name and price.

**Remember:**

> Lists use indexes to find values, while dictionaries use keys.

Dictionaries make it easier to organize and access related information using meaningful names.

---

**Think in Keys. Connect Values.**
