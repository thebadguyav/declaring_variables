#include<stdio.h>
int main()
{
    int a; //a variable 'a' of size 2 bytes gets declared in the memory
    int b=10; //a variable 'b' of size 2 bytes and equal to 10 gets declared in the memory
    printf("Enter the value of 'a'"); //user is asked to enter the value of 'a'
    scanf("%d \n",&a); //user enters the value of 'a'
    printf("The value of 'a' is: %d",a); //value of 'a' gets printed
    printf("The value of 'b' is: %d",b); //10 gets printed
return 0;
}
