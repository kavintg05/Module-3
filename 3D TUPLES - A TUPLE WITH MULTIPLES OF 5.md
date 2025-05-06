# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.NO-212223060119
#Name-Kavindra T G
N = int(input("Enter a number: "))
multiples_of_5 = tuple(i for i in range(5, N) if i % 5 == 0)
print("Multiples of 5 up to", N, "are:", multiples_of_5)


```

### OUTPUT
![image](https://github.com/user-attachments/assets/8bb24908-bbfe-4a8c-8333-7e8c1f670b8d)

### RESULT
Thus, the python program to create a tuple containing all multiples of 5 up to a given number **N** has been executed and verified successfully.
