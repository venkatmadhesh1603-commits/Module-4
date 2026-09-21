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
my_dict = {
    "banana": "yellow",
    "apple": "red",
    "grape": "purple",
    "orange": "orange"
}


sorted_by_keys = dict(sorted(my_dict.items()))


sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))


print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="901" height="416" alt="image" src="https://github.com/user-attachments/assets/dcb07387-0194-46b9-9f18-7f5e0435bc32" />


## Result
The dictionary is successfully sorted by keys and values in alphabetical order.



