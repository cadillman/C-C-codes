# C-C-codes

#include <stdio.h>
void modulo(int a,int b);
int main()
{
        int i,x,y;
        printf("Enter number\n");
        scanf("%d",&x);
        printf("Enter mod value\n");
        scanf("%d",&y);
        modulo(x,y);
        return 0;
}
void modulo(int a,int b)
{
        int k;
        k=a%b;
        if (k==0)
        {
                printf("Perfect modulo");
        }
        else
        {
                printf("Not perfect modulo");

        }
}
