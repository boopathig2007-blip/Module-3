# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
import re

text = input("Enter words: ")

words = text.split()

result = [word for word in words if not re.search(r'e', word, re.IGNORECASE)]

print("Words without 'e':")
for word in result:
    print(word)

## Output
Enter words: apple mango sky tree sun ball
Words without 'e':
mango
sky
sun
ball
## Result
Thus, the Python program using Regular Expressions to filter and display words without the letter 'e' was successfully executed and verified.
