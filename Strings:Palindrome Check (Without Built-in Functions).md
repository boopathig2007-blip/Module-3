# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
s = input("Enter a string: ")

reverse = ""

for i in range(len(s) - 1, -1, -1):
    reverse += s[i]

if s == reverse:
    print("Palindrome String")
else:
    print("Not a Palindrome String")

## Output
Enter a string: madam
Palindrome String
Enter a string: hello
Not a Palindrome String
## Result
Thus, the Python program to check whether a given string is a palindrome without using built-in string reversal functions was successfully executed and verified.
