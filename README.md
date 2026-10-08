# CSArrayList: A Custom ArrayList (Java)

COMP 282 Homework 3. A from scratch version of Java's `ArrayList`, built on a plain array that grows when it fills up, with JUnit tests.

## What is inside

| File | What it is |
|---|---|
| `src/CSArrayList.java` | The class. A generic list that extends `AbstractList<E>` and stores its items in an array |
| `src/CSArrayListLabTests.java` | 15 JUnit 5 tests for the list |
| `src/CSArrayListTest.java` | A small program you can run to try the list: it adds two items, then prints them, the size, and a few lookups |

## What the list can do

- Three constructors: empty, with a starting capacity, and copied from another collection
- `add` at the end or at an index, `get`, `set`, `size`, `isEmpty`, and `indexOf`
- `remove` by index or by value, and `clear`
- `ensureCapacity` and `trimToSize` to manage the size of the array
- A `toString` that prints the items in brackets, and prints `[]` for an empty list
- Automatic growth: when the array is full, a private `reallocate` method makes a bigger one

## How to run the tests

Open the project in IntelliJ IDEA. It is set up to use the JUnit 5 library. Right click `CSArrayListLabTests` and choose Run.
