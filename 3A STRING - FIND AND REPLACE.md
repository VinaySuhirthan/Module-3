# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To create a Python function convert that transforms each uppercase letter to lowercase, each lowercase letter to uppercase, and replaces all special characters with "bb".


### ALGORITHM

1. Begin the program.  
2. Define a function named convert that accepts a string as an argument.  
3. Initialize an empty result string.
4. Traverse each character in the input string:
    - If the character is uppercase, convert it to lowercase and add to the result.
    - If the character is lowercase, convert it to uppercase and add to the result.
    - If it is a special character (not a letter), add "bb" to the result.
5. Return the final result string.
6. Call the function with a test string and display the result.
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO:212222040120
#Name:PRASANNA R
def convert(a):
    new=""
    for i in range(0,len(a)):
        if a[i].isupper():
            new+=a[i].lower()
        elif a[i].islower():
            new+=a[i].upper()
        else:
            new+="bb"
    print(new)
            
```

### OUTPUT

![LAB3 DAY1](https://github.com/user-attachments/assets/616a8943-2aa4-43e7-bcc0-f33762adec66)


### RESULT
Thus, the Python program to convert uppercase to lowercase, lowercase to uppercase, and replace special characters with "bb" has been implemented and executed successfully.
