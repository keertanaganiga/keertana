#include <stdio.h>

void main()
{
    int n,a,b,c;
    printf("enter the number of triangle:\n");
    scanf("%d",&n);
    printf("enter the number of sides:\n");
    scanf("%d%d%d",&a,&b,&c);
    if(a!=b && b!=c)
    {
    printf("triangles are unique");
    }
    else
    {
    printf("not unique\n");
    }
}
