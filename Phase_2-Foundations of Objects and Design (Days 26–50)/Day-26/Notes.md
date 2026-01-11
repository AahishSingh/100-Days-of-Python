# Day 26 Notes — Python Object Model



## Everything Is an Object



Python does not have primitive types.



Examples of objects:

* int
* str
* list
* function
* class



```
x = 10
print(type(x))



What Defines an Object?
---



Every object has:

Identity → memory location

Type → what kind of object it is

Value → the data it holds



a = 100
print(id(a), type(a), a)



Variables Are References
---



Variables do not store values.
They store references to objects.

a = 10
b = a
print(id(a) == id(b))  # True



Mutability vs Immutability
---




Immutable Objects
---


int

float

str

tuple

They cannot be changed after creation.

x = 10
x += 1  # new object created



Mutable Objects
---



list

dict

set

They can be modified in place.

nums = \[1, 2]
nums.append(3)




Why This Matters
---



Mutability affects:

Shared references

Function behavior

Bugs and side effects

OOP design safety



Functions Are Objects Too
---



Functions can be assigned, passed, and stored.

def greet():
    return "Hello"

print(type(greet))


Mental Rule
---



Variables point to objects.
Objects have identity, type, and value.
Mutability defines behavior.

