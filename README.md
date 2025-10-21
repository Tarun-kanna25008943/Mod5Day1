# EX-01 Program to Convert a Floating-Point Number into an Integer

## AIM:
To write a C program that reads a floating-point number from the user and converts it into an integer.

## ALGORITHM:

1. Start
2. Declare a variable num of type float.
3. Read a floating-point number from the user using scanf("%f", &num).
4. Print the integer equivalent of the number using printf() with format specifier %.f (which removes the decimal part).
5. Stop

## PROGRAM:
```
#include <stdio.h>

int main()
{
    float num;
    printf("Enter a decimal number: ");
    scanf("%f",&num);
    printf("the integer equivalent of %.2f = %.f",num,num);
    return 0;
}
```
## OUTPUT:
<img width="664" height="130" alt="image" src="https://github.com/user-attachments/assets/fa60006a-d5f8-4d3b-b2da-a2569f6c1922" />

## RESULT:
The program successfully converts a floating-point number into its integer equivalent using type casting.
