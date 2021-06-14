#include<stdio.h>
int main()
{
int x=32,y=45;
printf("Before Swapping: x = %d,y = %d",x,y);
x = x+y;
y = x-y;
x = x-y;
printf("\nAfter Swapping: x = %d,y = %d",x,y);
return 0;
}
