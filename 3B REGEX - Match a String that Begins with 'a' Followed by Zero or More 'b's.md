# Exp.No:3b  
## REGEX - Match a String that Begins with 'a' Followed by Zero or More 'b's

---

### AIM  

To create a Python program that checks if a string starts with the letter 'a' and is followed by zero or more 'b' characters, using regular expressions. The string should contain only 'a' and 'b'.

### ALGORITHM

1.	Begin the program.
2.	Import the re module for regular expressions.
3.	Use input() to read a string from the user.
4.	Define a regex pattern ^ab*$:
    o	^ asserts the start of the string.
    o	a matches the character 'a'.
    o	b* matches zero or more 'b' characters.
    o	$ asserts the end of the string.
5.	Use re.fullmatch() to check if the entire string matches the pattern.
6.	Print "Matched!" if it matches, otherwise print "Not matched!".
7.	Terminate the program.


---

### PROGRAM

```
#Reg.NO:212222040120
#Name:PRASANNA R
import re
str=input()
x=re.match("^a(b*)$",str)
if x:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT

![LAB3 DAY2](https://github.com/user-attachments/assets/1c5437e5-ac68-4f11-b5a7-b53c3f834749)


### RESULT

Thus, the Python program to match a string that begins with 'a' followed by zero or more 'b's has been implemented and executed successfully.
