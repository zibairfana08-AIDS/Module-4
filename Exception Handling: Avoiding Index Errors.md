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
list1 = [10, 20, 30, 40, 50]


try:
   
    print("Accessing element at index 5:", list1[5])
except IndexError:
   
    print("You're out of list range")


print("Program continues after error handling.")
```

## Output
<img width="1028" height="241" alt="502948248-a355bb8c-e51d-46b8-8021-eb1245c78ee3" src="https://github.com/user-attachments/assets/083f296e-bef2-423a-aac0-4bc07a610dd3" />

## Result
the Python program that handles an IndexError when trying to access an element beyond the available range of a list is executed successfully.
