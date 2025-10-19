# num-sign
A code to find out whether a number is positive, negative or zero using user input.

#include<stdio.h>
int main()
{
int a;
printf("Enter a number to check whether its negative, positive or zero: ");
scanf("%d", &a);
if (a>0)
{
    printf("the number %d is positive.", a);
}
else if (a<0)
{
    printf("the number %d is negative.", a);
}
else 
printf("the number is zer0.");
    return 0;
}
