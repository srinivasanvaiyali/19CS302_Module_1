# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Calculate the number of years using the formula:
6. End .  

## Program:
```
/*
Program to find number of years based on principle,rate & simple interest.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008
*/
```
```
#include <stdio.h> 
#include <math.h> 
int main() 
{ 
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r); 
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n)); 
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci); 
return 0; 
}
```

## Output:

<img width="852" height="247" alt="438159349-fc4e3c25-2b86-451b-9ed7-a7b0692f4185" src="https://github.com/user-attachments/assets/aaeec1a4-26a4-4efd-83f2-7fc4cd54c5a0" />



## Result:
Thus the program was executed and the output was verified successfully.
