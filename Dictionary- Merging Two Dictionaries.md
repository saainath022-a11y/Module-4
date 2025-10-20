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

