# Power
#include<stdio.h>

void main()
{
    int x,n,i, result=1;
    printf("Enter base ");
    scanf("%d",&x);
    printf("Enter power ");
    scanf("%d",&n);

    for(i=0; i<n; i++)
    {
        result*=x;
    }
        printf("%d to the power %d = %d", x,n,result);

}
