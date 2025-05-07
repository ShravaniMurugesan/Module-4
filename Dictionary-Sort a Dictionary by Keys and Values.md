# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
# Start the program

# Define a dictionary with key-value pairs
data = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

# Sort by keys
sorted_by_keys = dict(sorted(data.items()))

# Sort by values
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))

# Display the original and sorted dictionaries
print("Original dictionary:", data)
print("Sorted by keys:", sorted_by_keys)
print("Sorted by values:", sorted_by_values)

```

## Sample Output
![image](https://github.com/user-attachments/assets/3d810934-8997-42f1-945d-4143b1a85d3e)

## Result
Program executed Successfully.
