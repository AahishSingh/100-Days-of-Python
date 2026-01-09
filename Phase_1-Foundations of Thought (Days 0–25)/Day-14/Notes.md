# Day 14 Notes — Tuples



## What is a Tuple?



A tuple is an **ordered collection of items** like a list,
but it is **immutable** (cannot be changed).



---

## Creating a Tuple



Syntax:
t = (1, 2, 3)



Single-element tuple:
t = (5,)   # comma is mandatory

Without comma → not a tuple.



---

## Tuple Characteristics



* Ordered
* Indexed
* Allows duplicate values
* Immutable



---

## Accessing Tuple Elements



Indexing:
t\[0]



Slicing:
t\[1:3]



---

## Immutability (Core Concept)



Once created, a tuple:

* Cannot add elements
* Cannot remove elements
* Cannot modify elements



This prevents accidental data changes.



---

## Tuple vs List



List:

* Mutable
* Uses \[]



Tuple:

* Immutable
* Uses ()



---

## When to Use Tuples



* Fixed data (coordinates, RGB values)
* Data that should not change
* As dictionary keys (later)
* Returning multiple values from functions
