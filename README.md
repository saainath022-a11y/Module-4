# SAAINATH.B

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

## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

Add code here
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}


def merge():
    merged_dict = {**dict1, **dict2}
    return merged_dict

result = merge()
print("Merged Dictionary:", result)

## Output
<img width="543" height="300" alt="mod 4 2" src="https://github.com/user-attachments/assets/a1b1371f-8519-446b-a5f6-ed8f39ebb8e4" />

## Result
Successfully wrote a Python program that merges two dictionaries and combines their key-value pairs.

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
Add Code here
my_dict = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}
sorted_by_keys = dict(sorted(my_dict.items()))
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)

## Sample Output
![Uploading mod 4 3.png…]()

## Result
Successfully wrote a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order

# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
Add code here
list1 = [10, 20, 30, 40]
try:
    value = list1[5]
    print("Accessed value:", value)
except IndexError:
    print("You're out of list range")

## Output
<img width="372" height="187" alt="mod 4 4" src="https://github.com/user-attachments/assets/6d2933b9-3393-4dab-8c5b-1d421e6517b4" />

## Result
Successfully wrote a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

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
Add code here
with open('story.txt', 'w') as file:
    file.write("This is the first line.\n")
    file.write("Another line begins here.\n")
    file.write("Totally tubular text.\n")
    file.write("hello world.\n")
    file.write("Testing again.\n")
    file.write("Final line.\n")

count = 0
with open('story.txt', 'r') as file:
    for line in file:
        stripped = line.lstrip()
        if stripped and stripped[0] != 'T':
            count += 1

print("Number of lines not starting with 'T':", count)
## Output
<img width="802" height="397" alt="mod 4 5" src="https://github.com/user-attachments/assets/cd3d8437-48f4-402b-a5e2-c8c30f328503" />

## Result
Successfully wrote a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.
