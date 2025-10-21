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
d={1:2,3:323,5:12,2:56,4:24,6:18}
sd=sorted(d.items(), key= lambda x : x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sd)
```

## Sample Output
<img width="1099" height="154" alt="Screenshot 2025-10-21 165839" src="https://github.com/user-attachments/assets/ed8b24fa-1fae-4621-8e30-2583d1aea861" />

## Result
Thus, the python program that sorts a dictionary alphabetically by keys and values is created successfully
