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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
result = [word for word in items if 'e' not in word]
print(result)
```
## Output
<img width="694" height="820" alt="529746236-1c890714-a951-46b2-8bd5-fe601f062f46" src="https://github.com/user-attachments/assets/ac98c372-aa4e-4ec6-83f8-6d3d7cb71151" />

## Result
Thus,the python program has been executed successfully.
