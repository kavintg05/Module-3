# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.NO-212223060119
#Name-Kavindra T G
def even_numbers_up_to_n():
    a = int(input("Enter a number: "))
    l = []
    for i in range(1, a):
        if i % 2 == 0:
            l.append(i)
    print("Even numbers up to", a, "are:", l)

even_numbers_up_to_n()


```

### OUTPUT
![image](https://github.com/user-attachments/assets/b5294a6d-bb67-4eb0-8757-5ef2fe8e5281)

### RESULT
Thus, the python program function that accepts a number **N** and creates a list containing all even numbers up to **N** has been executed and verified successfully
