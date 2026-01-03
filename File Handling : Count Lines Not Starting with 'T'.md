# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def count_lines_not_starting_with_T():
    count = 0
    with open("story.txt", "r") as file:
        for line in file:
            if not line.startswith('T'):
                count += 1
    return count
result = count_lines_not_starting_with_T()
print("Number of lines not starting with 'T':", result)
```
## Output
<img width="525" height="87" alt="image" src="https://github.com/user-attachments/assets/282602be-9cdb-4619-ae72-6dab6fb327be" />

## Result
Executed Successfully.
