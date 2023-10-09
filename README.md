
#include<stdio.h>
void printPattern(int n)
{
    int i,j,k;
    for(i=1;i<=n;i++)
    {
        for(k=1;k<=n-i;k++)
            printf(" ");
            for(j=1;j<=2*i-1;j++)
            printf("*");
            printf("\n");
    }
    return;
}
int main()
{
    int n;
    scanf("%d",&n);
    printPattern(n);
    return 0;
}
