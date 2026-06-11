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
# Define two dictionaries
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'d': 40, 'e': 50, 'b': 25}

# Define a function to merge dictionaries
def merge(d1, d2):
    return {**d1, **d2}

# Call the function and store the result
result = merge(dict1, dict2)

# Print the merged dictionary
print("Merged Dictionary:", result)
```

## Output
<img width="718" height="205" alt="image" src="https://github.com/user-attachments/assets/e16538cf-3b25-4f30-a8b8-1e4268942487" />

## Result
The above program has been executed successfully.
