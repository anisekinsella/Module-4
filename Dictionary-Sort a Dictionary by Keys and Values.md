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
my_dict = {3: "apple", 1: "banana", 6: "orange", 2: "mango", 5: "grape", 4: "pear"}
sorted_keys = sorted(my_dict.keys())
print("Keys are")
for key in sorted_keys:
    print(key, end=" ")
```

## Sample Output
<img width="480" height="214" alt="image" src="https://github.com/user-attachments/assets/4828d57a-b6f3-4528-bfee-067bf12c05fb" />

## Result
Executed Successfully.
