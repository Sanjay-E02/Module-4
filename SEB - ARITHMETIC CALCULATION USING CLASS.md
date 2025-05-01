# Exp.No:4E  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`, and `div`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform division  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.  
   - `div(self)`: Performs the division operation. If `b` is zero, returns an error message for division by zero.  
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `div()` method and print the result. Handle division by zero.  
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```
class saveetha:
def add(self,a,b):
return a+b
def mul(self,a,b):
return a*b

a = int(input())
b = int(input())
c = saveetha()
choice = 1

while choice!=0:
choice = int(input())
if choice == 1:
print("Result: ",c.add(a,b))
elif choice == 2:
print("Result: ",c.mul(a,b))
elif choice == 0:
print("Exiting!")
else:
print("invalid choice")


```

### OUTPUT
![image](https://github.com/user-attachments/assets/fddb6519-64ad-4100-b2e5-4982e55e73f2)

### RESULT
Thus, the python program is implemented and executed sucessfully.
