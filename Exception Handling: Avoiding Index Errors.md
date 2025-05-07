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
# Step 1: Define a list with some integer elements
list1 = [10, 20, 30]

# Step 2: Use try-except to handle out-of-range access
try:
    # Attempting to access an index that doesn't exist
    print("Accessing index 5:", list1[5])
except IndexError:
    # Step 3: Handle the exception and print a custom message
    print("You're out of list range")

```

## Output
![image](https://github.com/user-attachments/assets/c5d8c89c-fc4e-4bed-9e14-6b1d23399904)

## Result
Program executed successfully.
