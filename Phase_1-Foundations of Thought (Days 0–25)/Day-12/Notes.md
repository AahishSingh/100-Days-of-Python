# Day 12 Notes — List Operations & Methods

## Adding Elements to a List

### 1️⃣ `append()`
Adds an element to the end of the list.

```python
numbers = [10, 20, 30]
numbers.append(50)
print(numbers)  # [10, 20, 30, 50]
```

---

### 2️⃣ `extend()`
Adds multiple elements to the list.

```python
numbers.extend([60, 70])
print(numbers)
```

---

### 3️⃣ `insert()`
Adds an element at a specific index.

```python
numbers.insert(1, 15)
print(numbers)
```

---

## Removing Elements from a List

### 1️⃣ `remove()`
Removes the first occurrence of a value.

```python
numbers.remove(20)
print(numbers)
```

⚠ Raises an error if the value is not found.

---

### 2️⃣ `pop()`
Removes and returns an element by index.

```python
numbers.pop()      # Removes last element
numbers.pop(2)     # Removes element at index 2
```

---

## Other Useful Operations

```python
len(numbers)              # Number of elements
50 in numbers             # Membership check (True/False)
numbers.count(10)         # Count occurrences
numbers.index(30)         # Index of first occurrence
```

---

## Important Note

List methods modify the list **in place**.  
They usually return `None`.
