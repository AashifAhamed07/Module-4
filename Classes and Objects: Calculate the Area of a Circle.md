# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self):
        a = int(input())
        c = math.pi * (a * a)
        print(f"Area of circle: {c:.2f}")
obj = cse()
obj.mech()

```

## Output
<img width="699" height="193" alt="Screenshot 2025-10-20 213351" src="https://github.com/user-attachments/assets/28a2511a-8df9-4fd9-aa10-593034f286e1" />

## Result
Thus,the Python program that calculates the area of a circle based on the radius given by user and using class(cse) and method(mech) to perform a calculation is created successfully
