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
def merge(d1, d2):
    return {**d1, **d2}
dict1 = eval(input())
dict2 = eval(input())
merged_dict = merge(dict1, dict2)
print(merged_dict)
```
## Output
<img width="1269" height="174" alt="Screenshot 2025-10-21 164951" src="https://github.com/user-attachments/assets/796d5b62-0024-4463-990f-62ef7646959b" />

## Result
Thus,the python program that merges two dictionaries and combine ther key value pairs is executed successfully
