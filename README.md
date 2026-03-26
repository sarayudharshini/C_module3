# C_module3
# EX 3 C program to find number of years based on principle,rate & simple interest.
## AIM:
## DATE:17/03/2026
### AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Read Amount, Time, and Rate from the user.
2. Use the formula: Principal = Amount / (1 + Rate/100)^Time.
3. Calculate the principal value using the formula.
4. Display the principal amount.
  
### Algorithm:
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
Developed by: Sai Ranjani K
RegisterNumber:  212222060210
#include <stdio.h>
### Program:
```c program
#include <stdio.h> 
#include <math.h>

int main()
{
    float principal_amount, rate_of_interest, time,compound_interest;
    
    scanf("%f", &compound_interest);
    scanf("%f", &time);
    scanf("%f", &rate_of_interest);
    
    principal_amount = compound_interest / (pow((1 + (rate_of_interest / 100)), time));
    
    printf("Principle Amount is = %.2f", principal_amount);
    
    return 0;
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r);
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n));
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);
return 0;
}
*/
```

## Output:
### Output:

![image](https://github.com/user-attachments/assets/9970da37-69c1-4a73-b739-87ab076ce2db)
![image](https://github.com/user-attachments/assets/b1a66268-f110-4907-8820-75a6f0d765f4)


## Result:
### Result:
Thus the program was executed and the output was verified successfully.
