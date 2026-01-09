# Day 15 Notes — Sets



## What is a Set?



A set is an **unordered collection of unique elements**.

* No duplicates allowed
* No indexing
* Mutable (can be changed)



---

## Creating a Set



Syntax:
s = {1, 2, 3}



Empty set:
s = set()   # NOT {}

{} creates an empty dictionary.



---

## Set Characteristics



* Unordered
* Unique elements
* Mutable
* No indexing or slicing



---

## Adding \& Removing Elements



* add(value)
* remove(value) → error if value not present
* discard(value) → no error if value missing
* pop() → removes random element



---

## Set Operations



Union:
A | B   or   A.union(B)



Intersection:
A \& B   or   A.intersection(B)



Difference:
A - B   or   A.difference(B)



---

## When to Use Sets



* Remove duplicates
* Membership testing
* Mathematical set operations
* When order doesn’t matter
