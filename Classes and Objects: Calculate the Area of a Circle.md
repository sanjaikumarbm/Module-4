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
    def mech(self, radius):
        return math.pi * radius * radius

r = float(input("Enter the radius of the circle: "))
obj = cse()
print("Area of circle:", round(obj.mech(r), 2))
```

## Output
<img width="579" height="223" alt="image" src="https://github.com/user-attachments/assets/76dd60be-92c2-45fd-93e3-7f52a1688a50" />


## Result
Thus, the program is executed and output verified successfully
