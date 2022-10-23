//# Reverse-number.c//
#include<stdio.h>
int main()
{
    int no,d1,d2,d3,d4,sum,rev;
    printf("enter four digit number");
    scanf("%d",&no);
    d1=no/1000;
    no=no%1000;
    d2=no/100;
    no=no%100;
    d3=no/10;
    d4=no%10;
    sum=d1+d2+d3+d4;
    rev=(d4*1000)+(d3*100)+(d2*10)+d1;
    printf("\nsum=%d",sum);
    printf("\nreverse=%d",rev);
    return 0;
}
