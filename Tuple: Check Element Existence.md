# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program

t = tuple(map(int, input("Enter tuple elements separated by space: ").split()))

element = int(input("Enter element to search: "))

if element in t:
    print("Element found in the tuple")
else:
    print("Element not found in the tuple")



## Output
Enter tuple elements separated by space: 10 20 30 40 50
Enter element to search: 30
Element found in the tuple

## Result
Thus, the Python program to check the existence of an element in a tuple was successfully executed and verified.
