# EX-05-5a-POINTERS
## AIM:
Write a C program to convert a 23.65 into 25 using pointer
## ALGORITHM:
1. Declare a double variable to hold the floating-point number (23.65).
2. Declare a pointer to double to point to the address of the variable.
3. Use the pointer to modify the value to 25.0.
4. Print the modified value.
## PROGRAM:
```
# include<stdio.h>
int main()
{
float a,*b=&a;
scanf("%f",&a);
int ans,*val=&ans;
*val=(int)*b;
printf("the integer equivalent of %.2f =%d",a,*val);

```
## OUTPUT:

![image](https://github.com/Yogabharathi3/EX-05-5a-POINTERS/assets/118899387/3663fdb2-336c-4e42-89a1-8fde9ff8cd13)

## RESULT:
Thus the program to convert a 23.65 into 25 using pointer has been executed successfully.

