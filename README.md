# SIN-FN-CODE
#include <stdio.h>
#include <math.h>
int main()
{

float x,i,k,f,s=0,u,p;
printf("enter value in degree\n");
scanf("%d",&x);
p=(x*3.141592654/180);
for(i=0;i<x;i++)
{u=k;
f=1;
while(u!=0)
{f=f*u;
u--;
}
s=s*(pow(-1,i)*pow(p,k))/f;
k+=2;
}
printf("thje value of sine is %f is %f",x,s);
printf("\n the lib fn of sin %f is %f\n",x,sin(p));
}
