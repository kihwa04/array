# array
short array code
#include<stdio.h>
int main()
{
    int r,c;
    for(r=1;r<=5;r++)
    {
        for(c=1;c<=r;c++)
        printf("%d\t",c);
        printf("\n");
    }

    return 0;
}
