# Ex8 Deque
## DATE:
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. Start and define count(arr).
2. Initialize counter c = 0.
3. Loop through array from index 0 to MAX - 1.
4. If element is non-zero, increment c.
5. Return c and end.  

## Program:
```
Program to count the number of elements present in the deque
Developed by: SHAHIN J
RegisterNumber:  212223040190

#include <stdio.h>
#define MAX 10

int count(int *arr) {
    int c = 0, i;
    for(i = 0; i < MAX; i++) {
        if(arr[i] != 0) {
            c = c + 1;
        }
    }
    return c;
}
```

## Output:
![image](https://github.com/user-attachments/assets/fb7a8f92-6bca-48ac-98f4-6b282ea79d48)



## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
