# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1=[5, 10, 20] 

try: 

   print(list1[5]) 

except: 

   print("You're out of list range")
```
## Output
<img width="590" height="139" alt="440108978-41405ea3-b4d6-470d-98a0-80a8c37089b5" src="https://github.com/user-attachments/assets/2a1b6258-3fe1-44d6-87f7-0a46b2289b8b" />

## Result
Thus, the program has been successfully executed.
