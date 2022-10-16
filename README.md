# include<stdio.h>
int main(){int a=1,b=-1,c,N,i;
printf("enter the value of N");
scanf("%d",&N);

for(i=0;i;i++)
{
    c=a+b;
    printf("%d\n",c);
    a=b;
    b=c;
}
}
