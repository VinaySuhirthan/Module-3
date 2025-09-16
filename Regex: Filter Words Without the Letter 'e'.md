# 3b) Regex in Python: Filter Words Without the Letter 'e'

## Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## Program
```
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
a=[]
for i in items:
    if 'e' not in i:
        a.append(i)
print(a)
```
## Output
![444868753-99a48b2a-dee4-4f79-b07c-06bbf6884939](https://github.com/user-attachments/assets/6f778fd4-2143-4f6c-8392-f871c48a5bba)

## Result
Thus the program executed successfully.
