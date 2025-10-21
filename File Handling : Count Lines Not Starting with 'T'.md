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
def create_file(file_path,content):
    with open(file_path,'w') as file:
        file.write(content)
def print_lines_with_substring(file_path,substring):
    with open(file_path,"r") as file:
        for i in file:
            if substring in i:
                print(i.strip())
```
## Output
<img width="1832" height="210" alt="Screenshot 2025-10-21 172615" src="https://github.com/user-attachments/assets/ef5a637c-f250-49f1-b93e-e6f3bc8d9534" />

## Result
