# Exp.No:3c
## LIST - Display the Duplicate Items of a User-Entered List

---

### AIM  
To create a Python program that accepts a list from the user and displays all the duplicate items in it.

### ALGORITHM

1.	Begin the program.
2.	Read the list from the user using input() and convert it to a list of integers using map() and split()/eval().
3.	Create two empty lists: one for tracking seen items and one for storing duplicates.
4.	Traverse each item in the list:
   o	If the item is not in the seen list, add it to seen.
   o	If it is already in seen and not yet in duplicates, add it to the duplicates list.
5.	Display the list of duplicate items.
6.	Terminate the program.


### PROGRAM

```
#Reg.NO:212222040120
#Name:PRASANNA R
a=eval(input())
dup = []
c = []
for i in a:
    if i not in c:
        c.append(i)
    else:
        dup.append(i)
print("Duplicate items list :",dup)
```

### OUTPUT

![LAB3 DAY3](https://github.com/user-attachments/assets/6008cb98-51ff-45b8-890d-76751797a67e)


### RESULT
Thus, the Python program to display the duplicate items of a user-entered list has been implemented and executed successfully.
