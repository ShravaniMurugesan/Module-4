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
# Open the file in read mode
with open('story.txt', 'r') as file:
    count = 0  # Initialize counter

    # Iterate through each line
    for line in file:
        # Strip leading spaces and check if line doesn't start with 'T'
        if line.lstrip() and not line.lstrip().startswith('T'):
            count += 1

# Print the final count
print("Number of lines not starting with 'T':", count)

```
## Output
![image](https://github.com/user-attachments/assets/9e65f1bb-278f-40b4-98ba-a4a6914ad581)

## Result
Progam executed sucessfully
