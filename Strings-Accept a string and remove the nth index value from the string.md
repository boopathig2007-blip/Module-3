# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
s = input("Enter a string: ")
n = int(input("Enter the index to remove: "))

if 0 <= n < len(s):
    result = s[:n] + s[n+1:]
    print("String after removing character:", result)
else:
    print("Invalid index")

## Output
Enter a string: Python
Enter the index to remove: 2
String after removing character: Pyhon
## Result
Thus, the Python program to remove the character at the Nth index from a string was successfully executed and verified.
