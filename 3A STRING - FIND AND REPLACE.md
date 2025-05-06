# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO-212223060119
#Name-Kavindra T G
def replace_word():
    str1 = input("Enter the original string: ")
    replace_str = input("Enter the word to be replaced: ")
    str2 = input("Enter the new word: ")
    str3 = str1.replace(replace_str, str2)
    print("Original String:", str1)
    print("Modified String:", str3)

replace_word()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/843b52cd-594b-4845-9695-58dbcdf5fada)

### RESULT
Thus, the python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user has been executed and verified successfully.
