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
# Define a dictionary
dictionary = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'green',
    'orange': 'orange'
}

# Sort dictionary by keys
sorted_keys = dict(sorted(dictionary.items()))

# Sort dictionary by values
sorted_values = dict(sorted(dictionary.items(),
                            key=lambda item: item[1]))

# Display the dictionaries
print("Original Dictionary:", dictionary)
print("Dictionary sorted by keys:", sorted_keys)
print("Dictionary sorted by values:", sorted_values)
```

## Sample Output
<img width="1287" height="228" alt="image" src="https://github.com/user-attachments/assets/b936cfaf-5850-472f-baab-261af3180e18" />


## Result
The above program has been executed successfully.
