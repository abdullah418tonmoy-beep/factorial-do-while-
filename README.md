#include<stdio.h>
int main()
{
    int num,i=1,fact = 1;


    printf("Enter a num to define factorial: ");
    scanf("%d",&num);

   do
   {
       fact= fact*i;
       i++;
   }
   while( i <= num);
   printf("your factorial num is %d\n",fact);
    return 0;

}
