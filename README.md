# c-2
Third quadrant Triangle
#include <stdio.h>

int main()
{
    int n,i,j;
    printf("enter no.");
    scanf("%d",&n);
    for(i=n;i>=1;i--)
    {
        for(j=n-i;j>=1;j--)
        {
            printf("  ");
        } 
           for(int k=1;k<=i;k++)
           printf("* ");
        
        printf("\n");
    }
    return 0;
}
