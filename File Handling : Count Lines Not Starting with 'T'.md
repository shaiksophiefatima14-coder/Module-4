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
file = open("story.txt", "r")

# Initialize the counter
count = 0

# Read each line from the file
for line in file:
    # Check if the line does not start with 'T'
    if line[0] != 'T':
        count += 1

# Close the file
file.close()

# Display the result
print("Number of lines not starting with 'T':", count)
```

## Output
<img width="493" height="185" alt="image" src="https://github.com/user-attachments/assets/e3e34486-a465-45cf-ac4e-5201a27a8c26" />


## Result
The above program has been executed successfully.
