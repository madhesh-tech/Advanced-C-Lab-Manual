EXP NO:2 C PROGRAM FOR PASSING STRUCTURES AS FUNCTION ARGUMENTS AND RETURNING A STRUCTURE FROM A FUNCTION
Aim:
To write a C program for passing structure as function and returning a structure from a function

Algorithm:
1.	Define structure numbers with members a and b.
2.	Declare variable n of type numbers.
3.	Prompt the user to enter values for a and b.
4.	Input values for a and b into n using scanf.
5.	Call the add function with n as an argument.
6.	Print the result returned by the add function.
7.	Return 0
 
Program:

```
#include<stdio.h>
struct numbers
{
int a;
int b;
}n;
int add(struct numbers n);
int main()
{
scanf("%d %d ",&n.a,&n.b);
printf("%d",add(n));
}
int add(struct numbers n)
{
return n.a+n.b;
}

```




Output:

<img width="275" height="312" alt="image" src="https://github.com/user-attachments/assets/198bc9b5-c21a-4002-8cf2-768de5f7f57a" />





Result:
Thus, the program is verified successfully
