# c-programing-p7
/*WACP to read numbers from keyboard continuously till the press 999 and to find the sum of only positive numbers. */
#include<stdio.h>
int main()
{
    int num;
    int sum=0;
    printf("enter the positive numbers(enter 999 to quit):\n");
    scanf("%d",&num);
    while(num!=999)
        {
            sum=sum+num;
            scanf("%d",&num);
        }
    printf("\n the sum of all positive numbers=%d\n",sum);
    return 0;
        }
        output:
        enter the positive numbers(enter 999 to quit):
14
5
8
9
6
999

 the sum of all positive numbers=42
