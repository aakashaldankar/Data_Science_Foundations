# Dictionary Data Structure

## Introduction

A **dictionary** in Python is an unordered, mutable, and iterable collection of key-value pairs. It is one of the most versatile and widely used data structures in Python, providing a way to store and retrieve data efficiently using keys.

---

## Properties of a Dictionary

1. **Ordered**:  
   Dictionaries maintain the insertion order of keys and values (Python 3.7+).

2. **Mutable**:  
   The contents of a dictionary can be modified by updating, adding, or removing key-value pairs.

3. **Iterable**:  
   You can iterate through the keys, values, or items (key-value pairs) of a dictionary.

4. **Can Contain Various Data Structures**:  
   Dictionaries can hold values of any data type, including lists, tuples, sets, and even other dictionaries.

---

## Key Operations

### `del` Statement  
The `del` statement removes a specific key-value pair from the dictionary or deletes the entire dictionary.  

## list(dict)
Converts the dictionary keys into a list.

## Membership Testing (in Keyword)
Checks if a specific key exists in the dictionary.

## Methods in Dictionary

1. **get()**:
Returns the value of a key if it exists, else returns a default value.

2. **items()**:
Returns a view object containing key-value pairs.

3. **keys()**:
Returns a view object containing all keys.

4. **pop()**:
Removes a key and returns its value. Raises a KeyError if the key is not found.

5. **popitem()**:
Removes and returns the last inserted key-value pair.

6. **update()**:
Updates the dictionary with another dictionary or key-value pairs.

7. **values()**:
Returns a view object containing all the values.

8. **setdefault()**:
Returns the value of a key if it exists; otherwise, inserts the key with a default value.

---

## Dictionary Comprehension

Dictionary comprehension provides a concise way to create dictionaries from an iterable or another dictionary.

---


