# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
#Reg.NO-212223060119
#Name-Kavindra T G
import re

str1 = input("Enter the string: ")
pattern = r"ab{2,3}"
if re.match(pattern, str1):
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/95b98634-efb1-4b9e-8dc8-ebf92972f020)

### RESULT
Thus, the python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions has been executed and verified successfully.
