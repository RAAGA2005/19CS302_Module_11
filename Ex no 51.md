# EX 51 C program to reverse a string.
## DATE:21/05/2025
## AIM:
To write a C program to reverse a string.

## Algorithm
1. Start.
2. Define a variables.
3. Write a c program to reverse a string.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## Program:
```
#include <stdio.h>
#include <string.h>
int main() {
    char str[100], reversed[100];
    int length, i;
    printf("Enter a string: ");
    scanf("%s", str);  // Reads a single word
    length = strlen(str);
    for (i = 0; i < length; i++) {
        reversed[i] = str[length - i - 1];
    }
    reversed[length] = '\0'; // Null-terminate the reversed string
    printf("Reversed string: %s\n", reversed);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/ff2b7e35-7737-4d9c-a795-7630e24dffd7)

## Result:
Thus the program was executed and the output was verified successfully.
