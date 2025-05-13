# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

### PROGRAM

```
class pen:
    def _init_(self, a):
        self.a = a

    def stationary(self):
        print("Area of circle: {:.2f}".format(3.141592 * self.a * self.a))

# Take radius input from user
a = int(input())

# Create an object of class 'pen'
obj = pen(a)

# Call the function 'stationary' to display the area
obj.stationary()


```

### OUTPUT

![image](https://github.com/user-attachments/assets/c4ffc978-e03e-49c3-a29d-fa23c2814167)


### RESULT

Thus the python program for finding the area of the circle has been implemented and executed successfully.

