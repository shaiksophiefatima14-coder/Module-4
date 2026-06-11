# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of the circle =", area)

# Get radius from the user
radius = float(input("Enter the radius of the circle: "))

# Create an object of the class
obj = cse()

# Call the method to calculate the area
obj.mech(radius)
```

## Output
<img width="582" height="211" alt="image" src="https://github.com/user-attachments/assets/fc2f9458-b5ac-4dd0-9ce7-618b229a667c" />

## Result
The above program has been executed successfully.
