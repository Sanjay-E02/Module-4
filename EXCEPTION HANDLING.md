# Exp.No:4C  
## EXCEPTION HANDLING

---

### AIM  
To write a python program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

---

### ALGORITHM

1.Start

2.Take input numerator and denominator

3.Check:

4.If denominator == 0,

5.Set result = "You can't divide with 0"

6.Else,

7.Set result = numerator / denominator

8.Output result

9.End

---

### PROGRAM

```
a=int(input())
b=int(input())
try:
print(a/b)
except ZeroDivisionError:
print("You can't divide with 0")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/33f4004a-e86f-431e-8990-a0b15922b008)

### RESULT
Thus, the given python program is implemented and executed sucessfully.
