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
def remove(a):
    n=int(input())
    print(a[:n]+a[n+1:])
```

## Output

<img width="655" height="212" alt="530462210-1d8d3628-85be-47a6-99f4-bd47771603d9" src="https://github.com/user-attachments/assets/fde66a99-fb0a-41aa-9c05-d40a52044b35" />

## Result
Thus the program has been successfully executed

