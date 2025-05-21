# EX 55 C program to find a square of number using function with arguments without return type.
## DATE:21/05/2025
## AIM:
To write a C program to find a square of number using function with arguments without return type.

## ALGORITHM:

1. **Start**  
2. Define a function `findSquare(num)` that takes an integer argument.  
3. Inside the function, compute `num * num` and display the result.  
4. In the `main()` function:  
   - Accept an integer input from the user.  
   - Call `findSquare(number)` with the input value.  
5. **End**  


## PROGRAM:
```
#include <stdio.h>
void findSquare(int num) {
    printf("Square of %d is: %d\n", num, num * num);
}
int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    findSquare(number);
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/417382e7-5233-4f85-af71-e0b854b57f79)



## RESULT:
Thus the program was executed and the output was verified successfully.
