#include<stdio.h>
#include<conio.h>
Int main() 
{
 Int n1,n2;
 Printf("Enter two positive integers:");
 Scanf("%d%d",&n1,&n2);
 While(n1! =n2) 
{
 if(n1>n2) 
  n1=n2;
  else
  n2=n1;
 }
 Printf("Gcd=%d",n1);
return 0;
}
