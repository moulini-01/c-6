//# c-6
//strong number
#include <stdio.h>
int main()
{
    int num,fact=1,i;
    printf("enter the number:\n");
    scanf("%d",&num);
    i=num;
    while(i>0)
    {
        fact*=i;
        i--;
    }
    printf("factorial of %d is %d\n",num,fact);
    return 0;
}
    
