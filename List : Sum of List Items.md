# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

n = int(input("Enter the number of elements: "))

lst = []
for i in range(n):
    element = int(input())
    lst.append(element)

total = 0
for item in lst:
    total += item

print("Sum of list items =", total)

## Output
Enter the number of elements: 5
10
20
30
40
50
## Result
Thus, the Python program to find the sum of all items in a list was successfully executed and verified.
