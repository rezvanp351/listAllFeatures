# Python List Operations

This document demonstrates **common list operations in Python** with examples. You can use this file as a `README.md` for GitHub documentation. The corresponding Python code is also available in `list_operations_example.py`.

---

## 1. Access List Items
```python
my_list = [10, 20, 30, 40, 50]
print("Original List:", my_list)
print("First item:", my_list[0])
print("Last item:", my_list[-1])
```

---

## 2. Change List Items
```python
my_list[1] = 25
print("After changing index 1:", my_list)
```

---

## 3. Add List Items
```python
my_list.append(60)
print("After append:", my_list)
my_list.insert(2, 15)
print("After insert at index 2:", my_list)
```

---

## 4. Remove List Items
```python
my_list.remove(40)
print("After removing 40:", my_list)

popped_item = my_list.pop()
print("After pop (removed:", popped_item, "):", my_list)

del my_list[0]
print("After deleting first item:", my_list)
```

---

## 5. Loop Lists
```python
for item in my_list:
    print(item)
```

---

## 6. List Comprehension
```python
squares = [x**2 for x in range(1, 6)]
print("Squares:", squares)
```

---

## 7. Sort Lists
```python
unsorted_list = [3, 1, 4, 5, 2]
unsorted_list.sort()
print("Sorted list:", unsorted_list)

unsorted_list.sort(reverse=True)
print("Sorted in descending order:", unsorted_list)
```

---

## 8. Copy Lists
```python
copied_list = my_list.copy()
print("Copied list:", copied_list)
```

---

## 9. Join Lists
```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]

joined_list = list1 + list2
print("Joined using +:", joined_list)

list1.extend(list2)
print("Joined using extend:", list1)
```

---

## 10. List Methods
```python
numbers = [5, 3, 8, 3, 9]
print("Original numbers:", numbers)

print("Count of 3:", numbers.count(3))
print("Index of 8:", numbers.index(8))

numbers.reverse()
print("Reversed list:", numbers)

numbers.clear()
print("Cleared list:", numbers)
```

---

## Usage
- Save this as `README.md` for GitHub documentation.
- Run the separate file `list_operations_example.py` to test all operations in Python.
