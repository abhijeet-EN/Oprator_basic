
// #include<stdio.h>
// int main ()
// // WAP to add two nuber
// {
// 	int a,b,c;
// 	printf("enter first number:");
// 	scanf("%d",&a);
// 	printf("enter sec nmber :");
// 	scanf("%d",&b);
// 	c=a+b;
// 	printf("%d \n",c);
// //wap subtract of two interger
// 	int sub,quotient;
// 	sub=a-b;
// 	printf("%d \n",sub);
// //WAP multiupy and quotient of two number 
// 	int multi;
// 	multi=a*b;
// 	printf("%d \n",multi);
// 	quotient=a/b;
// 	printf("%d",quotient);
// //wap find remender of two number 
// 	int rem=a%b;
// 	printf("%d",rem); 
// 	return 0;
// }
// WAP to find avrage of three number 
// #include<stdio.h>
// int main()
// {
// 	int a,b,c,d;
// 	printf("enter the number three number :");
// 	scanf("%d %d %d",&a,&b,&c);
// 	d=(a+b+c)/3;
// 	printf("%d",d);
// 	return 0;
// }



// WAP convert c into f temp
// #include<stdio.h>
// int main ()
// {
// 	float c,fr;
// 	printf("enter the value of c:");
// 	scanf("%f",&c);
// 	fr=(c*1.8)+32;
// 	printf("%f",fr);
// 	return 0;
// }
// WAP swap two number 
// #include<stdio.h>
// #include<conio.h>
// int main ()
// {
// 	int a,b,c;
// 	printf("enter first number :");
// 	scanf("%d",& a);
// 	printf("enter the sec number :");
// 	scanf("%d",&b);
// 	printf("print a and b before swap ");
// 	printf("%d",a);
// 	printf("\t %d",b);
// 	c=a;
// 	a=b;
// 	b=c;
// 	printf("\nafter swaping: %d %d",a,b);
// 	getch;
// }
// cheak two number are equal ya not eyual
// #include<stdio.h>
// int main ()
// {
// 	int num1,num2;
// 	printf("enter the first number :");
// 	scanf("%d",&num1);
// 	printf("enter the second number :");
// 	scanf("%d",&num2);
// 	printf("%d",num1==num2);
// 	return 0;
// }
// #include<stdio.h> 
// int main()
// {
// 	int num1,num2, num3;
// 	printf("enter the first number :");
// 	scanf("%d",&num1);
// 	printf("enter the second number :");
// 	scanf("%d",&num2);
// 	printf("enter the third number :");
// 	scanf("%d",&num3);
// 	printf("%d", (num1>num2)&&(num1>num3));
// 	printf("%d", (num2>num1)&&(num2>num3));
// 	printf("%d", (num3>num1)&&(num3>num2));
// 	return 0;
// }
// whaek wheak number is zero
// #include<stdio.h>
// int main ()
// {
// 	int a;
// 	printf("enter the number a:");
// 	scanf("%d",&a);
// 	printf("%d",a==0);
// 	printf("%d",a>=18);#vote ke liye eligiable 
// 	return 0;
// }
// find even odd use basic oprator
// #include<stdio.h>
// int main ()
// {
// int a;
// printf("enter the number :");
// scanf("%d",&a);
// 	printf(" even:%d ",a%2==0);
// 	printf("odd: %d",a%2!=0);
// 	return 0;
// }
// cheak whather year is leap year 
// #include<stdio.h>
// int main ()
// {
// 	int year;
// 	printf("Enter the year :");
// 	scanf("%d",&year);
// 	(year%4==0)?printf("leap is year"):printf("year is normal year ");
// }


// cheak number lies in btw 10 se 50 
// #include<stdio.h>
// int main ()
// {
//     int a;
//     printf("Enter the number :");
//     scanf("%d",&a);
//     (a>=10 && a<=50)?printf("number lie "):printf("number is not lie ");
//     return 0;
// }

// determine the whather student pass 
// #include<stdio.h>
// int main ()
// {
//      int marks;
//      printf("Enter the marks :");
//      scanf("%d",&marks);
//      (marks<=33)?printf("student is fail "):printf("student is pass ");
//      return 0;
// } 

// Check whether a number is divisible by both 3 and 5.
// #include<stdio.h>
// int main ()
// {
//     int num ;
//     printf("Enter the number :");
//     scanf("%d",&num);
//     (num%3==0 && num%5==0)?printf("divisible "):printf("is not divisiable ");
//     return 0;
// }

// Determine whether a character is a vowel.
// #include<stdio.h>
// int main ()
// {
//     char ch;
//     printf("Enter the chacter :");
//     scanf("%c",&ch);
//     (ch=='a' ||ch=='e' ||ch=='i' ||ch=='o' ||ch=='u')?printf("chacter is vowel "):printf("charcter is not vowel");
//     return 0;
// }

//  Check whether a triangle is valid.
// #include<stdio.h>
// int main ()
// {
//     int a,b,c;
//     printf("enter the triangle side :");
//     scanf("%d %d %d",&a,&b,&c);
//     (a=b&&b=c)?printf("valid triangle"):printf("invalid trianlge ");
//     return 0;
// }
// 31. Use += to add 10 to a number.
// • 32. Use -= to subtract 5 from a number.
// • 33. Use *= to multiply a number by 2.
// • 34. Use /= to divide a number by 4.
// • 35. Use %= to find the remainder after division by 3.
// #include<stdio.h>
// int main ()
// {
//     int a=25;
//     int sub =(a-=10);
//     printf("%d\n",a+=10);
//     printf("%d\n",a-=10);
//     printf("%d\n",sub);
//     printf("%d\n",a*=10);
//     printf("%d\n",a/=10);
//     printf("%f\n",a%=3);
//     return 0;
// }

// calculate the simple interesrt
// #include<stdio.h>
// int main ()
// {
//     float si,rate,time,amount;
//     printf("Enter the amount :");
//     scanf("%f",&amount);
//     printf("Enter the rate :");
//     scanf("%f",&rate);
//     printf("Enter the time:");
//     scanf("%f",&time);
//     si =(amount*rate*time)/100;
//     printf("simple interest = %f",si);
//     return 0;
// }

//  update salary after adding bonus #incomplete 
// #include<stdio.h>
// int main ()
// {
//     int salary,bonus;
//     printf("Enter the salry:");
//     scanf("%d",&salary);
//     printf("Enetr the bonus:");
//     scanf("%d",&bonus);
//     int total = salary+bonus;
//     printf("%d",salary);
//     printf(" new salary =%d",total);
//     return 0;
// }

// increase the price 5pecent rate 
// #include<stdio.h>
// int main ()
// {
//     int price,rate =5;
//     printf("Enter the prince:");
//     scanf("%d",&price);
//    int  mrp =price+((price*5)/100);
//     printf("%d",mrp);
//     return 0;
// }

//  57. Find the larger of two numbers using the ternary operator.
// #include<stdio.h>
// int main ()
// {
//     int num1,num2;
//     printf("Enter the number1:");
//     scanf("%d",&num1);
//     printf("Enter the number 2:");
//     scanf("%d",&num2);
//     (num1>num2)?printf("number 1 is large"):printf("number 2 large ");
//     return 0;
// }

// cheak even odd 
// #include<stdio.h>
// int main ()
// {
//     int a;
//     printf("Enter the number :");
//     scanf("%d",&a);
//     (a%2==0)?printf("number is even"):printf("number is odd");
//     return 0;
// }
// int max = (a > b) ? ((a > c) ? a : c) : ((b > c) ? b : c);
    

//find amximum among three using nested terntry opretor
#include<stdio.h>
int main ()
{
    int a,b,c;
    printf("Enter the value of a:");
    scanf("%d",&a);
     printf("Enter the value of b:");
    scanf("%d",&b);
     printf("Enter the value of c:");
    scanf("%d",&c);
   int max = (a > b) ? ((a > c) ? a : c) : ((b > c) ? b : c);

}