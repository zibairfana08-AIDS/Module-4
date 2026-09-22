# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
try:
    with open('story.txt', 'r') as file:
        count = 0  

        
        for line in file:
            if not line.lstrip().startswith('T'):
                count += 1

    
    print(f"Number of lines not starting with 'T': {count}")

except FileNotFoundError:
    print("The file 'story.txt' was not found.")
```

## Output
<img width="1012" height="252" alt="502948539-d65446df-6cc1-449b-b823-95b9ea03f35c" src="https://github.com/user-attachments/assets/27a7438d-760d-404a-8e1c-ffc173bb8ae0" />


## Result
the Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is executed successfully.
