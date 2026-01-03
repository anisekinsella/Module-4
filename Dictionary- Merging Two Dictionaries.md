## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1=eval(input())
dict2=eval(input())
dict2.update(dict1)
print(dict2)
```
## Output
<img width="659" height="144" alt="image" src="https://github.com/user-attachments/assets/52b829db-43d3-4d85-b229-27828126041a" />

## Result
Executed Sueccessfully.
