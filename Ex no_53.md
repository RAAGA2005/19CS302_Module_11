# EX 53 C program to remove duplicates in an array.
## DATE:21/05/2025
## AIM:
To write a C program to remove duplicates in an array.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to remove duplicate elements in an array.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
## Program:
```
#include <stdio.h>
void removeDuplicates(int arr[], int *n) {
    int temp[*n];
    int index = 0;
    for (int i = 0; i < *n; i++) {
        int duplicate = 0;
        for (int j = 0; j < index; j++) {
            if (arr[i] == temp[j]) {
                duplicate = 1;
                break;
            }
        }
        if (!duplicate) {
            temp[index++] = arr[i];
        }
    }
    for (int i = 0; i < index; i++) {
        arr[i] = temp[i];
    }
    *n = index;
}
int main() {
    int n;
    printf("Enter the number of elements: ");
    scanf("%d", &n);
    int arr[n];
    printf("Enter the elements: ");
    for (int i = 0; i < n; i++) {
        scanf("%d", &arr[i]);
    }
    removeDuplicates(arr, &n);
    printf("Array after removing duplicates: ");
    for (int i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }
    
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/96af1fa5-0e06-4639-a3d5-f19bf941c0a2)



## Result:
Thus the program was executed and the output was verified successfully.
