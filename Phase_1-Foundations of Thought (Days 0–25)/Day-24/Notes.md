# Day 24 Notes — Modules \& Imports



## What is a Module?



A module is a file containing Python code (functions, variables, classes)
that can be reused in other programs.



Example:
math, random, datetime



---

## Importing Modules



1. import module
   Use module.function()



Example:
import math
math.sqrt(16)



---

2. from module import name
   Use name directly.



Example:
from math import sqrt
sqrt(16)



---

3. Aliasing
   Rename modules for convenience.



Example:
import math as m
m.pi



---

## Built-in Modules (Common)



* math → mathematical operations
* random → randomness
* datetime → dates and time
* os → interacting with OS (later)
* sys → system-level details (later)



---

## Why Modules Matter



* Avoid rewriting code
* Organize large programs
* Improve readability
* Encourage reuse
