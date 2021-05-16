#include<stdio.h>
 int prime(int n, int k)

{ 
if (k==0)

return 1;

if(n%k==0 && k!=1)

return 0;

else {

if(n%k!=0 && k!=1)

return prime(n, k-1); 
else
 return 1;

}

}

int main()

{

int n;

printf("Enter a Number: ");

scanf("%d",&n);

if(prime(n,n-1))

printf("\n %d is a prime number",n);
else

printf("\n %d is not a prime number",n);

return 0;

}
