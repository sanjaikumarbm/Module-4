# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
dictionary = {'b': 2, 'a': 1, 'c': 3}

sorted_by_keys = dict(sorted(dictionary.items()))
sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))

print("Original:", dictionary)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)
```

## Sample Output
<img width="613" height="242" alt="image" src="https://github.com/user-attachments/assets/74f496b1-1bbc-4bf2-945a-831f86009d6e" />


## Result
Thus,the program is executed and output verified successfully
