# Outcome 3 - Iterators, Generators and Decorators

**Skill Description**
----------
Understanding how to use slightly more advanced Python techniques. Major coverage areas here include:

- Iterators
- Generators
- Decorators


**Output**
----------
After attaining this skill, and as a demonstration of it, a person should be able to do the following:

1. Complete at least 5 of these challenges
  - [Code Kata 1](http://linktosomekata)
  - [Code Kata 2](http://linktosomekata)
  - [Code Kata 3](http://linktosomekata)
  - [Code Kata 4](http://linktosomekata)
  - [Code Kata 5](http://linktosomekata)
  - [Code Kata 6](http://linktosomekata)
  - [Code Kata 7](http://linktosomekata)


**Objectives**
----------
## **Knowledge**


| Knowledge Unit   |      Studied      | Memorized |
|:-------------|:------------------:|:--------:|
| Iterable objects in Python - Lists, String, Dictionaries, Tuples, Sets, Generators - and how they work | [ ] | [ ]  |
| Creating an iterator using the `iter()` function | [ ] | [ ]  |
| Creating an iterable class by overriding the `__iter__()` and `next()` methods | [ ] | [ ]  |
| Common functions that accept iterators as arguments - `sum()`, `map()`, `reduce()`, `filter()`, `list()` etc. | [ ] | [ ]  |
| Generators as functions that create a sequence of values as opposed to a single value | [ ] | [ ]  |
| The `yield` keyword in generators used to return a single value | [ ] | [ ]  |
| Using generator expressions to create generators on the fly | [ ] | [ ]  |
| Performance comparisons of generators versus regular iterable objects | [ ] | [ ]  |
| Interesting methods available in the `itertools` module for working with iterators like `chain()`, `izip()` | [ ] | [ ]  |
| Functions as objects - Can be passed as parameters to other functions, Can be assigned to variables, Can be defined in other functions | [ ] | [ ]  |
| Accessing data from inner functions | [ ] | [ ]  |
| Composition of decorators and Python's decorator syntax | [ ] | [ ]  |
| Applying decorators to function | [ ] | [ ]  |
| Debugging decorated functions | [ ] | [ ]  |



----------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:-------------|:------------------:|:--------:|
| **Context:** When I want to use iterator functionality within my program... **Action:** I create an iterator object using the `iter()` function. | [ ] | [ ] |
| **Context:** When I want to make a objects of a class iterable... **Action:** I override the `next()` and `__iter__()` functions. | [ ] | [ ] |
| **Context:** When overriding the `__iter__()` method of a class... **Action:** I return the object (`self`). | [ ] | [ ] |
| **Context:** When overriding the `next()` method of a class... **Action:** I ensure to indicate the end of the interation by raising a `StopIteration` exception. | [ ] | [ ] |
| **Context:** When using an iterator in my program... **Action:** I call the `next()` method to get the next item in the collection I'm iterating over. | [ ] | [ ] |
| **Context:** When I am creating a generator... **Action:** I use `yield()` to indicate a value to be returned. | [ ] | [ ] |
| **Context:** When I want to create a generator on the fly (on a single line)... **Action:** I use generator expressions. | [ ] | [ ] |
| **Context:** When I need to modify the behaviour of many functions in a uniform manner... **Action:** I make use of decorators. | [ ] | [ ] |



----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I believe that I can pass an iterator to any function that works with accepts iterable objects. | [ ] | [ ]  |
| I believe using generators can increase the performance of my application. | [ ] | [ ]  |
| I believe using decorators makes my code more reusable. | [ ] | [ ]  |
