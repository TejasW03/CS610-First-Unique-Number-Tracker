# CS610-First-Unique-Number-Tracker

Python implementation of a data structure that efficiently tracks the first unique number in a stream of integers.

## Features

- Adds numbers to the stream
- Returns the first non-repeating number at any point
- Achieves O(1) average time using a hashmap and a doubly linked list

## Example

```python
firstUnique = FirstUnique([6, 8, 15, 15])
print(firstUnique.showFirstUnique())  # Output: 6

firstUnique.add(6)
print(firstUnique.showFirstUnique())  # Output: 8

firstUnique.add(8)
print(firstUnique.showFirstUnique())  # Output: -1
```

###Originally completed as part of CS610 coursework at NJIT.
