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
def remove(a):
   
    for i in range(len(a)):
        if i != b:
            print(a[i],end="")
b = int(input())
```

## Output
<img width="761" height="230" alt="Screenshot 2026-06-02 133408" src="https://github.com/user-attachments/assets/e362734e-1425-476b-b27b-8b40ded831ef" />


## Result
The given program is executed and verified successfully
