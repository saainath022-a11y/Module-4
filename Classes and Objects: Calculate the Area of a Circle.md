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

Add code here
import math
pi_value=math.pi
class cse:
    def mech(self,radius):
        circle_area=(radius**2)*(pi_value)
        return round(circle_area,2)
radius=int(input())
circle1=cse()
print("Area of circle:",circle1.mech(radius))

## Output
<img width="602" height="187" alt="mod 4 1" src="https://github.com/user-attachments/assets/c504ac0c-6f5f-4d7c-b0ae-17367e86f25a" />

## Result
Successfully wrote a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

