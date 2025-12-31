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
def count_lines_not_starting_with_T(filename):
    count = 0  
    with open(filename, "r") as file:
        for line in file:
            if not line.startswith('T'):
                count += 1
    return count

result = count_lines_not_starting_with_T("story.txt")
print("Number of lines that not starting with 'T':", result)
```
## Output

<img width="809" height="193" alt="530067545-2701fb81-bba2-404d-877c-519b750117ff" src="https://github.com/user-attachments/assets/19cc6b04-a1ed-4aa6-8efc-6dcc1180a309" />

## Result
Thus , the program has been executed succesfully.

