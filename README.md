#include <stdio.h>
int main(){

int n,rem,rev=0;
scanf("%d",&n);

for(;n!=0;n/=10)
{
rem=n%10;
rev=rev*10+rem;
}
printf("the reverse of a given number is %d",rev);



return 0;
}
