# 3d) Strings-Palindrome Check in Python (Without Built-in Functions)

## Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## Program
```
a=input()
s=a[::-1]
if a==s:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```

## Output
![444870990-1b21809c-9d7d-40a1-ab29-3100c9b0493e](https://github.com/user-attachments/assets/9ad8fee8-1c36-4512-9ad7-49bc855c68da)

## Result
Thus the program executed successfully.
