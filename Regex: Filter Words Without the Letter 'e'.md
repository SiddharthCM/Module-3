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
def remove(s):
    n = int(input()) 
    print(s[:n] + s[n+1:])
```
## Output
<img width="784" height="834" alt="529873870-344b684b-33af-4450-a33a-8d79d788d76d" src="https://github.com/user-attachments/assets/00429964-105d-43eb-96e2-116936cb626e" />

## Result
Thus,the python program has been executed successfully.
