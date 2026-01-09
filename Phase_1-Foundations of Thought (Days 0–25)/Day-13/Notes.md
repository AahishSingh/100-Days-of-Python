# Day 13 Notes — List Slicing & Copying

## List Slicing
Slicing allows you to extract a portion of a list.

Syntax:
list[start:end:step]

- start → inclusive
- end → exclusive
- step → jump size (optional)

---

## Examples
numbers = [0, 1, 2, 3, 4, 5]

numbers[1:4]     → [1, 2, 3]
numbers[:3]      → [0, 1, 2]
numbers[3:]      → [3, 4, 5]
numbers[::2]     → [0, 2, 4]
numbers[::-1]    → reversed list

---

## Negative Indexing
Negative indices count from the end.

numbers[-1] → last element
numbers[-3:-1] → elements near the end

---

## Copying Lists (IMPORTANT)

❌ Wrong way:
a = b

This does NOT create a copy.
Both variables point to the same list.

✅ Correct ways:
a = b.copy()
a = b[:]

---

## Key Rule
Assignment copies the reference.
Slicing or copy() creates a new list.
