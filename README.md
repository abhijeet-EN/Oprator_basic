#include<stdio.h>
void Name() 
{
	printf("abhi\n");
}
void main ()
{
	Name();
	Name();
	Name();
}
#include<stdio.h>
void sum(int a,int b)
{
	int c=a+b;
	printf("%d",c);
}
void main ()
{
	
	sum(200,560);
}
#include<stdio.h>
int rollno()
{
	return 1;
}
int main ()
{
	int c=rollno();
	printf("%d",c);
	return 0;
}
#include<stdio.h>
int add(int a,int b,int c)
{
	printf("%d",a+b+c);
	return 0;
}
int main ()
{
	add(10,30,50);
	return 0;
}

create a function to find square and cube
#include<stdio.h>
int square(int a)
{
	printf("enter the value :");
	scanf("%d",&a);
	printf("%d\n",a*a);
	printf("%d",a*a*a);
	return 0;
}
int main ()
{
	int a;
	square(a);
	printf("\n");
	square(a);
	return 0;
}
create a function to cheak even odd
#include<stdio.h>
int evodd(int a)
{
	printf("enter the number :");
	scanf("%d",&a);
	if(a%2==0)
	{
		printf("number is even ");
	}
	else
	{
		printf("number is odd");
	}
	return 0;
}
int main ()
{
	int a;
	evodd(a);
	evodd(a);
	return 0;
}
#include<stdio.h>
int big(int a,int b)
{
	printf("enter the value a and b :");
	scanf("%d %d",&a,&b);
	if (a>b)
	{
		printf("a is max and b is small");
	}
	else 
	{
		printf("b is max and a is small");
	}
return 0;	
}
int main ()
{
	big(5,9);
	return 0;
}
