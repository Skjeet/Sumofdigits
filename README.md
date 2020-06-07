# Sumofdigits
#include<stdio.h>
main()
{
	int a,b=0;
	printf("Enter the number : ");
	scanf("%d",&a);
	while(a!=0)
	{
		int c=a%10;
		b=b+c;
		a=a/10;
	}
	printf("Sum of digits is %d",b);
}
