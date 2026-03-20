# Exp.No:3a
## STRING - CASE CONVERSION AND SPECIAL CHARACTER REPLACEMENT

### AIM  
To write a Python program that demonstrates string manipulation using character case conversion and special character replacement.

### ALGORITHM

1. Begin the program.
2. Define the function convert(str1) to process the input string.
3. Initialize an empty string result.
4. Traverse each character in str1:
5. If the character is uppercase, convert it to lowercase using .lower().
6. If the character is lowercase, convert it to uppercase using .upper().
7. If the character is not alphanumeric (i.e., a special character), append "bb" instead.
8. Return or print the transformed string.
9. Terminate the program.

### PROGRAM

```
def convert(n):
    s=""
    for i in n:
        if i.islower():
            s = s + i.upper()
        elif i.isupper():
            s = s + i.lower()
        else:
            s = s + "bb"
    print(s)
```

### OUTPUT

![image](https://github.com/user-attachments/assets/0c0ea4cf-e562-4145-ad29-27d2c9142f19)


### RESULT
Thus the Python program is successfully transformed the string according to the specified rules.
