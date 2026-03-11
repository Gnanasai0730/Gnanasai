                                                           //09-03-2026//Monday
//To display our name.
#include<stdio.h>
int main()
{
printf("My name is SAI");
printf("Welcome to SIMATS");
return 0;
}

//To find area of square
#include<stdio.h>
int main()
{
int side;
int area;
scanf("%d",&side);
area=side*side;
printf("%d",area);
return 0;
}

//To add two integer values
#include<stdio.h>
int main()
{
int a,b;
int c;
scanf("%d%d",&a,&b);
c=a+b;
printf("%d",c);
return 0;
}

//add two floating points
#include<stdio.h>
int main()
{
float a,b;
float sum;
scanf("%f%f",&a,&b);
sum=a+b;
printf("%f",sum);
return 0;
}

//To find the area of circle
#include<stdio.h>
int main()
{
float r;
float area;
scanf("%f",&r);
area=3.14*r*r;
printf("%f",area);
return 0;
}

//To find area and perimeter of rectangle
#include<stdio.h>
int main()
{
int l,b,area,perimeter;
scanf("%d%d",&l,&b);
area=l*b
perimter=2*(l+b);
printf("%d",area);
printf("%d",perimeter);
return 0;
}

//To find area of the traingle
#include<stdio.h>
int main()
{
float a,b,area;
scanf("%f%f",&a,&b);
area=0.5*a*b;
printf("%f",area);
return 0;
}

//Converting celsius to fahrenheit scale
#include<stdio.h>
int main()
{
float C,F;
scanf("%f",&C);
F=(C*9/5)+32;
printf("%f",F);
return 0:
}

//To convert Fahrenheit to celsius scale
#include<stdio.h>
int main()
{
float C,F;
scanf("%f",&F);
C=(F-32)*5/9;
printf("%f",C);
return 0;
}

//To find the Simple interest
#include<stdio.h>
int main()
{
float P,T,R,SI;
scanf("%f%f%f",&P,&T,&R);
SI=(P*T*R)/100;
printf("%f",SI);
return 0;
}

                                                          //10-03-2026//Tuesday
//Find the area of circle
#include<stdio.h>
void main()
{
constant float pi=3.14;
float r=10,area;
area=pi*r*r;
printf("%.2f",area);
}

//FInd the area of circle using define
#include<stdio.h>
#define pi 3.14
void main()
{
int r;
float area;
area=pi*r*r;
printf(".2f",area);
}

//decimal to octal
#include<stdio.h>
void main()
{
int a=20;
printf("Octal number=%o",a);
}

//decimal to hexa
#include<stdio.h>
void main()
{
int a=20;
printf("Hexadecimal=%x",a);
}

//Octal to decimal
#include<stdio.h>
void main()
{
int a=010;
printf("Decimal=%d",a);
}

//Hexadecimal to decimal
#include<stdio.h>
void main()
{
int a=0x15;
printf("Decimal=%d",a);
}

//Print character and find ASCII value
#include<stdio.h>
void main()
{
char ch='g';
printf("ch=%c\n",ch);
printf("ch=%d,hence an integer\n",ch);
printf("ch1=%c\n,ch+1);
printf("ch1=%d,hence an integer",ch+1);
}

//To find quotient and ramainder
#include<stdio.h>
int main()
{
int a=5;
int q,r;
q=a/2;
r=a%2;
printf("Quotient=%d\n",q);
print("Remainder=%d",r);
return 0;
}

//Area of traingle
#include<stdio.h>
int main()
{
int b=3,h=3;
float area;
area= (1/2.0)*b*h;
printf("Area=%.2f",area);
return
}

//To swap two integers using third variable
#include<stdio.h>
int main()
{
int a=10,b=20,t;
printf("a=%d\tb=%d\n",a,b);
t=a;
a=b;
b=t;
print("a=%d\tb=%d",a,b);
return 0;
}

//Swapping without third variable
#include<stdio.h>
int main()
{
int a=10,b=20;
printf("a=%d\tb=%d\n",a,b);
a=b;
b=a/2;
printf("a=%d\tb=%d",a,b);
return 0;
}

//To dispaly a number if it is negative
#include<stdio.h>
int main()
{
int number;
scanf("%d",&number);
if (number<0){
printf("You entered %d\n",number);
}
printf("The if statement is easy");
return 0;
}

//To find whether a integer is odd or even
#include<stdio.h>
int main()
{
int n;
printf("Enter the number= ");
scanf("%d",&number);
if (n%2==0){
printf("%d is even",n);
}
else{
printf("%d is odd",n);
}
return 0;
}

//Eligible to vote or not
#include<stdio.h>
int main()
{
int age;
printf("Enter the age =");
scanf("%d",&age);
if (age>18)
{
print("%d is eligible to vote",age);
}
else{
printf("%d is not elligible to vote",age);
}
return 0;
}

//To find a student pass or fail
#include<stdio.h>
int main()
{
int n;
printf("Enter the n= ");
scanf("%d",&n);
if (n>=35)
{
printf("%dis pass",n);
}
else
{
printf("%d is fail",n);
}
return 0;
}

//To convert days into months and days
#include<stdio.h>
int main()
{
int totaldays;
int months,days;
printf("Enter totaldays= ");
scanf("%d",&totaldays);
months=totaldays/30;
days=totaldays%30;
printf("months="%d/n",months);
printf("days="%d",days);
return 0;
}

//To convert days into years,months and days
#include<stdio.h>
int main()
{
int Totaldays;
int years,months,days;
printf("Enter Totaldays=");
scanf("%d",Totaldays);
years=Totaldays/365;
months=Totaldays%365;
days=Totaldays%30;
printf("Years=%d\n",years);
printf("Months=%d\n",months);
printf("Days=%d",days);
return 0;
}

//To find the grade of a student
#include<stdio.h>
int main()
{
int marks;
printf("Enter the marks= ");
if (marks<0||marks>100){
printf("Number is invaid");
}
else if (marks>=90){
printf("Grade=S");
}
else if (marks>=80){
printf("Grade=A");
}
else if (marks>=70){
printf("Grade=B);
}
else if (marks>=60){
printf("Grade=C");
}
else if (marks>=50){
printf("Grade=D");
}
else(marks<50){
printf("Fail");
{
return 0;
}

//Finding the greatest number
#include<stdio.h>
int main()
{
int c=10,b=22,a=9;
if (a>b){
if (a>c);
printf("%d",a);
else;
printf("%d",c);
}
else{
if (b>=c);
printf("%d",b);
else;
printf("%d",c);
}
return 0;
}

//To find grade by percentage
#include <stdio.h>
int main()
{
int percentage;
scanf("%d",&percentage);
if (percentage>=0&&percentage<=100){
if (percentage>=90){
printf("Grade=S\n");
}else{
if (percentage>=80){
printf("Grade=A\n");
}else{
if (percentage>=70){
printf("grade=B\n");
}else{
if (percentage>=60){
printf("grade=C\n")
}else{
if (percentage>=50){
printf("grade=D\n")
}else{
if percentage<50){
print("grade=F");
}
}
}
}
}
else{printf("invalid")}
return 0;
}

                                                         //11-03-2026//Wednesday
//to find maximum number among 3 numbers
#include <stdio.h>
int main()
{
int n1,n2,n3;
scanf("%d%d%d",&n1,&n2,&n3);
if ((n1>n2)&&(n1>n3)){
printf("max=%d",n1);
}else if(n2>n3){
printf("max=%d",n2);
}else{
print("max=%d",n3);
}
return 0;
}

//To check a number is b/w 1-100
#include <stdio.h>
{
int n;
scanf("%d",&n);
if (n>=1&&n<=100){
printf("within range");
}else{ 
printf("out of range");
}
return 0;
}

//To check whether a number is divisible by 3 or 5
#include <stdio.h>
{
int n;
scanf("%d",&n);
if (n%3==0||n%5==0){
printf("divisible by 3 or 5");
}else{
printf("not divisible");
}
return 0;
}

//To find Pre-Increment
#include <stdio.h>
void main()
{
int x,i;
i=10
x=++i;
printf("x=%d\n",x);
printf("i=%d",i);
}

//To find Post-Increment
#include <stdio.h>
void main()
{
int x,i;
i=10
x=i++;
printf("x=%d\n",x);
printf("i=%d",i);
}

//By using Conditional Operator
#include <stdio.h>
void main()
{
int a=10,b=20;
int max;
max=(a>b)?a:b;
printf("max=%d",max);
}

//program to find days using switch program
#include <stdio.h>
int main()
{
int day;
printf("enter no.(1-7)");
scanf("%d",&day);
switch(day){
case 1:
printf("monday");
break;
case 2:
printf("tuesday");
break;
case 3:
printf("wednesday");
break;
case 4:
printf("thursday");
break;
case 5:
printf("friday");
break;
case 6:
printf("saturday");
break;
case 7:
printf("sunday");
break;
default:
printf("invalid input");
}
return 0;
}

//program for break statement
#include <stdio.h>
int main()
{
int i;
for (i=1;i<=10,i++){
if (i==5)
break;
printf("%d\n",i);
}
return 0;
}

//program for continue statement
#include <stdio.h>
int main()
{
int i;
for (i=1;i<=10;i++){
if (i==5)
continue;
printf("%d\n",i);
}
return 0;
}

//program for goto statement
#include <stdio.h>
int main()
{
int i=1;
start:
if (i<=5){
printf("%d\n",i);
i++;
goto start;
}
return 0;
}

//to print HI using while loop
#include <stdio.h>
void main()
{
int i=1;
while (i<=10)
{
printf("HI\n");
i++;
}
printf("end");
}

//To print HI uding for loop
#include <stdio.h>
void main()
{
for (int i=1;i<=10;i++)
{
printf("hi\n");
}

//To display 1-10 using while loop
#include <stdio.h>
void main()
{
int i=1;
while (i<=10)
{
printf("%d\n",i);
i++;
}
printf("end");
}

//to diaplay 1-10 in reverse order using while loop
#include <stdio.h>
void main()
{
int i=10;
while (i>=1)
{
printf(0"%d\n",i);
i--;
}
printf("end");
}

//to display odd numbers
#include <stdio.h>
void main()
{
int i=1;
while(i<=10)
{
if(i%2!=0)
{
printf("%d\n",i);
}
i++;
}
printf("end");
}

//to diaplay even numbers
#include <stdio.h>
void main()
{
int i=1;
while(i<=10)
{
if (i%2==0)
{
printf("%d\n",i);
}
i++;
}
printf("end");
}

//To find sum of first 10 natural numbers
#include <stdio.h>
void main()
{
int i=1,sum;
while(i<=10)
{
sum=sum+i;
i++;
}
printf("sum=%d\n",sum);
printf("end");
}

//Sum of first 10 odd numbers
#include <stdio.h>
void main()
{
int i=1,sum=0;
while(i<=10)
{
if (i%2!=0)
{
sum=sum+i;
}
i++;
}
printf("sum=%d\n",sum);
printf("end");
}

//Sum of first 10 even numbers
#include <stdio.h>
void main()
{
int i=1,sum=0;
while(i<=10)
{
if (i%2==0)
{
sum=sum+i;
}
i++;
}
printf("sum=%d\n",sum);
printf("end");
}

//to find the factorial of a given number
#include <stdio.h>
void main()
{
int i=1,fact=1;
while (i<=5)
{
fact=fact*i;
i++;
}
printf("factorial=%d\n",fact);
printf("end");
}

//To print the fibonacci series
#include <stdio.h>
void main()
{
int i=0,first=0,second=1,next;
while (i<=10)
{
printf("%d\n",first);
next=first+second;
first=second;
second=next;
i++;
}
}

//




