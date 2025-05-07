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

# Step 1: Get user input
radius = float(input("Enter the radius of the circle: "))

# Step 2: Define the class
class cse:

    # Step 3: Define the method
    def mech(self, r):
        area = math.pi * (r ** 2)
        print("Area of the circle is:", area)

# Step 4: Execute the program
obj = cse()         # Create object
obj.mech(radius)    # Call method
```

## Output
![image](https://github.com/user-attachments/assets/2ca94c7d-a066-45a6-80a3-578e87086972)

## Result
Program executed successfully.
