## Task

# Write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

## Note

There is not built in max function in C. Code that will be reused is often put in a separate function, e.g. int max(x, y) that returns the greater of the two values.

## Input Format

Input will contain four integers - a,b,c,d , one on each line.

## Output Format

Print the greatest of the four integers.
Note: I/O will be automatically handled.
## AIM:
To write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.
## ALGORITHM:
1. Start.
2. Define a variables.
3. Write a program to calculate maximum function.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## PROGRAM:
```
#include<stdio.h>
int compare(int a[4])
{
    int max=a[0];
    for(int i=0;i<4;i++)
    {
        if(a[i]>max)
        max=a[i];
    }
    return max;
}
int main()
{
    int a[4];
    for(int i=0;i<4;i++)
    scanf("%d",&a[i]);
    int d= compare(a);
    printf("%d",d);
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/e2947f75-9e72-4329-899e-219f084864f0)
## RESULT:
Thus, the program is executed and verified successfully.
