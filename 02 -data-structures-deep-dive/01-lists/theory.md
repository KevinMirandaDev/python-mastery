# Lists
If you're reading this, thank you for following my progress.  
The previous stage focused on mastering data structures.  
Now it's time to control how programs make decisions.

Lists in Python — Theory
In Stage 01 I saw what lists are in a general way.
Now the goal is different:
Not only to know lists exist, but to truly understand how they work and how to use them in real code.
Small steps, but stronger steps.

## What is a list?
Like I learned before in Stage 01, a list is a data structure that allows us to store multiple values in a single variable.
Example:
``` python
numbers = [1, 2, 3, 4, 5]
``` 
Instead of creating many variables, we keep everything together in one place.
This makes programs simpler, cleaner, and easier to manage.

## Key Characteristics

### Lists are ordered
Lists keep the order of the elements.
Instead of scattering information...

``` python
letter_1 # "a"
letter_2 # "b"
letter_3 # "c"
```

We gather it.

``` python
letters = ["a", "b", "c"]
``` 
"a" is first
"b" is second
"c" is third
The position of each element is called its index.
Python starts counting from zero, not one.

letters[0]  # "a"
letters[1]  # "b"
letters[2]  # "c"
This felt strange at first, but now I see it is normal in programming.
### Lists are mutable
This is one of the most important ideas.
Mutable means the list can change after it is created.
We can modify elements inside the list. So if I do this:

``` python
numbers = [1, 2, 3]
numbers[0] = 10
``` 
Now the list becomes:

``` python
[10, 2, 3]

``` 
This flexibility is very powerful, and it is one reason lists are used everywhere in Python.
Lists can store different data types
A list is not limited to only numbers or only text.

``` python
mixed = [1, "hello", True, 3.14]

``` 
This freedom is useful, but in real programs it is often better to keep similar types together for clarity.
Clean code is easier to understand.
### Length of a list
We can know how many elements a list has using len().

``` python
numbers = [1, 2, 3, 4]
len(numbers)  # 4
```

This is very common when working with loops or validations.
### Why lists are important
Lists are one of the most used tools in Python.
They allow us to:
- store collections of data
- repeat actions with loops
- organize information
- prepare data for real applications
Without lists, many real programs would be impossible or very messy.
So mastering lists is not a small step.
It is part of building strong foundations.

---
``` python
Personal reflection
In the past, I learned things quickly and moved on fast.
Now I am trying to learn with patience and depth.
Understanding lists deeply may look simple,
but strong structures are built on simple stones.
I want to be a man standing on the rock, not on the sand.
So I take this step seriously, even if it is small.
Bible verse
“Everyone then who hears these words of mine and does them will be like a wise man who built his house on the rock.”
— Matthew 7:24

``` 
