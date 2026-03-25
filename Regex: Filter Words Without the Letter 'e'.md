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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result=[]
for w in items:
    if not re.search(r'e',w):
        result.append(w)
print(result)
```
## Output
<img width="658" height="147" alt="530461996-997ac3f8-656c-448e-ba44-0444b73acb71" src="https://github.com/user-attachments/assets/14615467-a514-4250-8342-bac9b684d983" />



## Result
Thus, the program has been successfully executed.

