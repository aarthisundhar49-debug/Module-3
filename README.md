# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = list(map(int, input().split()))
total = sum(numbers)
print("Sum of all elements =", total)
```
## Output
<img width="343" height="85" alt="image" src="https://github.com/user-attachments/assets/d8ac6429-c394-4382-a641-49e10b647f05" />

## Result
the program has been excecuted successfully

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
```
import re
words = input().split()
result = [word for word in words if not re.search('e', word)]
print("Words without 'e':", result)
```
## Output
<img width="523" height="108" alt="image" src="https://github.com/user-attachments/assets/16eb32d9-84af-4a1f-ad2d-987f2380a0cc" />

## Result
the program has been excecuted successfully

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
```
text = input()
index = int(input())
new_text = text[:index] + text[index+1:]
print("String after removing character:", new_text)
```
## Output
<img width="549" height="344" alt="image" src="https://github.com/user-attachments/assets/64e3f067-3c9a-4773-8a62-8853e12a5139" />

## Result
the program has been excecuted successfully
