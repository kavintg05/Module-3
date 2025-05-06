# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO-212223060119
#Name-Kavindra T G
def process_string():
    s = input("Enter a string: ")
    sliced = s[2:10]
    reversed_sub = sliced[::-1]
    result = reversed_sub[::2]
    print("Processed string:", result)

process_string()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/f44ae8c4-0866-4d73-9b66-6634ace3823c)

### RESULT
Thus, the python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string has been executed and verified successfully.
