# EX 16 C program to find minimum between three integer numbers using conditional operator.
## DATE:
## Aim:
To write a C program to find minimum between three integer numbers using conditional operator.

## Algorithm:
1. Start. 
2. Define a variables a,b,c,min. 
3. Write program to find minimum numbers. 
4. Read the value using scanf. 
5. Ask the user to make an input. 
6. Print out the answer. 
7. End.

## Program:
```
#include <stdio.h>
int main()
{
    int a,b,c;
    scanf("%d %d %d",&a,&b,&c);
    int min=(a<b)?(a<c?a:c):(b<c?b:c);
    printf("Minimum between %d, %d and %d = %d",a,b,c,min);
}
Developed by:Venkatasubramaniam R
RegisterNumber:212222060288
```

## Output:
![Screenshot 2025-05-07 075106](https://github.com/user-attachments/assets/163fb9b1-ca51-461f-90ea-785b916fa2a7)

## Result:
Thus the program was executed and the output was verified successfully.
