## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
# Define two dictionaries with some key-value pairs
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

# Define a function to merge dictionaries
def merge():
    merged_dict = {**dict1, **dict2}
    return merged_dict

# Call the function and print the result
result = merge()
print("Merged dictionary:", result)

```

## Output
![image](https://github.com/user-attachments/assets/76961842-2103-4b4d-b041-f948c30ae258)


## Result
Program executed successfully
