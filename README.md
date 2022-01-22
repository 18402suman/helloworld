#include<stdio.h>
int main() {
    int i, j, k, n;
    printf("enter the number of line \n");
    scanf("%d",&n);
    for(i=1;1<=n;i++)
    {
        for(j=n;j>i;j--)
        {
            printf(" ");
        }
        for(k=1;k<=1;k++)
        {
            printf("*");
        
        }
        printf("\n");
    }
}
