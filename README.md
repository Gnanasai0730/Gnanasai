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

                                                         //12-03-2026//Thursday
//To print an integer reverse
#include <stdio.h>
void main()
{
int n,rev=0;
scanf("%d",&n);
while(n!=0)
{
int digit=n%10;
rev=rev*10+digit;
n=n/10;
}
printf("reversed=%d",rev);
}

//To print a number is palindrome
#include <stdio.h>
void main()
{
int n,O,remainder,rev=0;
scanf("%d",&n);
O=n;
while (n!=0)
{
remainder=n%10;
rev=rev*10+digit;
n=n/10;
}
if (O==rev)
printf("palindrome");
else 
printf("not");
}

//To print a number is amstrong number or not
#include <stdio.h>
void main()
{
int n,O,rev=0;
scanf("%d",&n);
O=n;
while(n!=0)
{
int digit=n%10;
rev=rev+digit*digit*digit;
n=n/10;
}
if (rev==O)
printf("amstrong no."rev);
else 
printf("not",rev);
}

//To print sum of digits
#include <stdio.h>
void main()
{
int n,digit,sum=0;
scanf("%d",&n);
while (n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
printf("sum=%d",sum);
}

//To print a number is happy number
#include <stdio.h>
int main()
{
int n,O,digit,sum;
scanf("%d",&n);
O=n;
while (O!=1&&O!=4)
{
sum=0;
while (O>0)
{
digit=O%10;
sum=sum+digit*digit;
O=O/10;
}
O=sum;
}
if (O==1)
printf("%d id happy number",n);
else
printf("%d is not happy number",n);
return 0;
}

//To print a number is automorphic
#include <stdio.h>
int main()
{
int n,sq,O;
scanf("%d",&n);
sq=n*n;
O=n;
while (O>0)
{
if (O%10!=sq%10)
{
printf("not");
return 0;
}
O=O/10;
sq=sq/10;
}
printf("automorphic");
return 0;
}

//To print a number is harshad number or not
#include <stdio.h>
void main()
{
int n,O,digit,sum=0;
scanf("%d",&n);
O=n;
while(n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
if(O%sum==0)
{
printf("harshad no.");
}else{
printf("not")
}
}

//To print a number is magic number or not
#include <stdio.h>
int main()
{
int n,O,digit,sum;
scanf("%d",&n);
O=n;
while(n>9)
{
sum=0;
while(n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
}
if(n==1)
printf("magic no.");
else 
printf("not");
return 0;
}

//To print even number using for loop
#include <stdio.h>
void main()
{
for (int i=1;i<=10;i++)
{
if(i%2==0)
{
printf("%d\n",i);
}
}
}

//To find sum of n-natural numbers using for loop
#include <stdio.h>
void main()
{
int i,sum,=0,n;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
sum=sum+i;
}
printf("sum=%d\n",sum);
}

//to print first n even numbers using for loop
#include <stdio.h>
void main()
{
int i,sum=0,n;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (i%2==0)
{
sum=sum+i;
}
}
printf("%d\n",i);
}

//To find factorial using for loop
#include <stdio.h>
void main()
{
int i,fact=1,n;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
fact=fact*i;
}
printf("fact=%d\n",fact);
}

//To print multiplication table
#include <stdio.h>
void main()
{
int i,n,m;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
m=n*i
}
printf("%dX%d=%d\n",i,n,m);
}

//To print factors of given number
#include <stdio.h>
void main()
{
int i,n;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (n%i==0)
printf("factors=%d\n",i);
}
}

//To find given number is perfect or not
#include <stdio.h>
void main()
{
int i,n,sum=0,t;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (n%i==0)
{
sum=sum+i;
}
}
if(t==sum)
{
printf("%d is perfect",t);
}else{
printf("%d is not perfect",t);
}
}

                                                            //13-03-2026//Friday
//To find the given number is prime or not
#include<stdio.h>
void main()
{
    int num,i,isPrime=1;
    printf("Enter the number: ");
    scanf("%d",&num);
    if (num<=1){
        isPrime=0;
    }
    else{
        for(i=2;i<=num/2;i++){
            if(num%i==0){
                isPrime=0;
                break;
            }
        }
    }
    if(isPrime){
        printf("%d is a prime number");
    }
    else{
        printf("%d is not a prime number");
    }
}

//To find the prime numbers in a given set of numbers
#include<stdio.h>
int main()
{
    int num,i,j,isPrime;
    printf("Enter the number: ");
    scanf("%d",&num);
    for(i=2;i<=num;i++){
        isPrime=1;
        for(j=2;j<=i/2;j++){
            if(i%j==0){
                isPrime=0;
                break;
            }
        }
        if(isPrime){
            printf("%d is a Prime number.\n",i);
        }
    }
    return 0;
}

//Program to find the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for (i=1;i<=5;i++)
    {
        for (j=1;j<=5;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

//To print the hallow pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=n;j++){
            if(i==1||i==n||j==1||j==n){
                printf("*");
            }
            else{
                printf(" ");
             }
        }
        printf("\n");
         }
         return 0;
         }

//To print the staircase of stars
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for (i=1;i<=n;i++){
        for (j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("%d",i);
        }
        printf("\n");
    }
    return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for (i=5;i.=1;i--){
for (j=1;j<=i;j++){
printf("*");
}
printf("\n");
}
return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for(i=5;i>=1;i--){
for(j=1;j<=i;j++){
printf("%d",j);
}
printf("\n");
}return 0;
}

//To print the given pattern
#include<stdio.h>
int main()
{
    int n,i,j;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    for (i=n-1;i>=1;i--){
        for(j=1;j<=i;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
    

}

//To print the given pattern
#include<stdio.h>
int main()
{
    int i,j,s;
    
  for(i=1;i<=5;i++){
        for(s=1;s<=5-i;s++){
            printf(" ");
        }
        for(j=1;j<=i;j++){
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}

//To print the given pattern
#include<stdio.h>
void main()
{
    int i,j,n,num;
    num=1;
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
            printf("%d",num);
            num++;
        }
        printf("\n");
    }
}

//To print the given pattern
#include<stdio.h>
int main()
{
int n,i,j;
scanf("%d",&n);
for (i=1;i<=n;i++){
for (j=1;j<=n-j;j++){
printf(" ");
}
for(j=1;j<=(2*i-1);j++){
if(i==1||i==n||j==1||j==(2*i-1)){
printf("*");
}
else{
printf(" ");
}
printf(" ");
}
printf("\n");
}
return 0;
}

//To print the palindrome number
#include <stdio.h>
int main()
{
int n, rev = 0, r, temp;
printf("Enter a number: ");
scanf("%d", &n);
temp = n;
while(n > 0)
{
r = n % 10;
rev = rev * 10 + r;
n = n / 10;
}
if(temp == rev)
printf("Palindrome number");
else
printf("Not a palindrome");
return 0;
}

                                                         //14-03-2026//Saturday
//TO print multiplication table
#include <stdio.h>
void main()
{
int i,n,m;
scanf("%d",&n);
for (i=0;i<=n;i++)
{
m=n*i;
}
printf("%dX%d=%d\n",i,n,m);
}
}

//To print factors of given number
#include <stdio.h>
int main()
{
int i,n;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if(n%i==0)
{
printf("factors=%d\n",i);
}
}
return 0;
}

//to find LCM of two numbers
#include <stdio.h>
int main()
{
int a,b,max;
scanf("%d%d",&a,&b);
max=(a>b)?a:b;
while (1)
{
if(max%a==0&&max%b==0)
{
printf("LCM=%d",max);
}
max++;
}
return 0;
}

//To find GCD of given numbers
#include <stdio.h>
int main()
{
int a,b,i,gcd;
scanf("%d%d",&a,&b);
for (i=1;i<=a&&i<=b;i++)
{
if(a%i==0&&b%i==0)
{
gcd=i;
}
printf("%d",gcd);
}
return 0;
}

//To print the below pattern
#include <stdio.h>
int main()
{
int,i,n,j;
scanf("%d",&n);
for (i=n;i>=1;i--)
{
for (j=1;j<=i;j++)
{
printf("%d",i);
}
printf("\n");
}
return 0;
}

//To print the below pattern
#include <stdio.h>
int main()
{
int i,j,n;
scanf("%d",&n);
for (i=n;i>=1;i--)
{
for (j=1;j<=i;j++)
{
printf("%d",j);
}
printf("\n");
}
return 0;
}

//To print a number is perfect square or not
#include <stdio.h>
#include <math.h>
int main()
{
int n;
scanf("%d",&n);
int r=sqrt(n);
if(r*r==n)
printf("perfect sq");
else
printf("not");
return 0;
}

//To read and display numbers using array
#include <stdio.h>
void main()
{
int i,a[5],n;
scanf("%d",&n);
for (i=0;i<n;i++)
{
scanf("%d",&a[i]);
}
printf("displaying integers:");
for (int i=0;i<n;++i)
{
printf("%d\n",a[i]);
}
}

//To display array values in reverse order
#include <stdio.h>
void main()
{
int i,a[5],n;
scanf("%d",&n);
for (i=0;i<n;i++)
{
scanf("%d",&a[i]);
}
printf("displaying integers:");
for (int i=n-1;i>=0;i--)
{
printf("%d\n",a[i]);
}
}

//To find sum of array elements
#include <stdio.h>
void main()
{
int i,n,a[100],sum=0;
scanf("%d",&n);
for (i=0;i<n;i++)
{
scanf("%d",&a[i]);
printf("display integers");
}
for (int i=0;i<n;i++)
{
sum=sum+a[i];
}
printf("%d",sum);
}

//To find average of given array elements
#include <stdio.h>
void main()
{
int i,n,a[100],sum=0,avg;
scanf("%d",&n);
for (i=0;i<n;i++)
{
scanf("%d",&a[i]);
printf("display integers:");
for (int i=0;i<n;i++)
{
sum=sum+a[i];
}
avg=sum/n;
printf("AVG=%d",avg);
}
}

//To find largest element in an array
#include <stdio.h>
int main()
{
int arr[100], n, i, largest;
printf("Enter the number of elements: ");
scanf("%d", &n);
printf("Enter %d elements:\n", n);
for(i = 0; i < n; i++)
{
scanf("%d", &arr[i]);
}
largest = arr[0];   // assume first element is largest
for(i = 1; i < n; i++)
{
if(arr[i] > largest) 
{
largest = arr[i]; 
}
}
printf("The largest element in the array is: %d", largest);
return 0;
}

//To search a given element in an array
#include <stdio.h>
int main()
{
int arr[100], n, i, key, found = 0;
printf("Enter number of elements: ");
scanf("%d", &n);
printf("Enter the elements:\n");
for(i = 0; i < n; i++)
{
scanf("%d", &arr[i]);
}
printf("Enter the element to search: ");
scanf("%d", &key);
for(i = 0; i < n; i++)
{
if(arr[i] == key)
{
printf("Element found at position %d", i + 1);
found = 1;
break;
}
}
if(found == 0)
{
printf("Element not found");
}
return 0;
}

//To print a number is composite or not
#include <stdio.h>
int main()
{
int n,i,count=0;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if(n%i==0)
{
count++;
}
}
if(count>2)
{
printf("%d is a composite number");
}else{
printf("%d is not a composite number");
}
return 0;
}

                                                  //16-03-2026//Monday
//To read a string
#include <stdio.h>
int mmain()
{
char name[20];
scanf("%s",name);
printf("your name is %s",name);
return 0;
}

//To find length of the string
#include <stdio.h>
#include <string.h>
int main()
{
char str[50]="gnana sai";
int len=strlen(str);
printf("lenght of the string:%d",len);
return 0;
}

//To convert to lowercase,uppercase,string reverse
#include <stdio.h>
#include <string.h>
int main()
{
char str[50]="GNANA SAI";
char str1[50]="gnana sai";
char str2[50]="GNANA SAI';
strlwr(str);
strupr(str1);
strrev(str2);
printf("lowercase:%s\n",str);
printf("uppercase:%s\n",str1);
printf("reverse:%s",str2);
return 0;
}

//To compare two strings
#include <stdio.h>
#include <string.h>
int main()
{
char s1[20]="gnana sai";
char s2[20]="rahul sai";
if (strcmp(s1,s2)==0)
{
printf("s1&s2 are equal");
}else{
printf("s1&s2 are different");
}
return 0;
}

//To append and copy two strings
#include <stdio.h>
#include <string.h>
int main()
{
char s1[50]="gnana sai";
char s2[50]="dasararaju";
strcat(s1,s2);
printf("output string is:%s\n",s1);
strcpy(s1,s2);
printf("output string is:%s",s1);
return 0;
}

//To find length of the string without string function
#include <stdio.h>
int main()
{
char str[50]="dasararaju gnana sai";
int i=0,len=0;
while (str[i]!="\0")
{
len++;
i++
}
printf("length:%d",len);
return 0;
}

//To count no. of words in a string without string function 
#include <stdio.h>
int main()
{
char str[100]="DASARARAJU GNANA SAI";
int i,count=1;
for (i=0;str[i]!="\0";i++)
if (str[i]=='')
{
count++;
}
printf("no. of words=%d",count);
return 0;
}

//To concantenate two strings without string function
#include <stdio.h>
int main()
{
char str1[20]="dasararaju";
char str2[20]="gnana sai";
int i=0,j=0;
while (str1[i]!='\0')
{
i++;
}
while (str2[j]!='\0')
{
str1[i]=str2[j];
i++;
j++;
}
str[i]='\0';
printf("%s",str1);
return 0;
}

//To convert lower to uppercase without using string function
#include <stdio.h>
int main()
{
char str[20]="gnanasai";
int i=0;
while(str[i]!='\0')
{
if(str[i]>='a'&&str[i]<='z')
{
str[i]=str[i]-32;
}
i++;
}
printf("%s",str);
return 0;
}

//To convert upper to lowercase without using string function
#include <stdio.h>
int main()
{
char str[20]="GNANASAI";
int i=0;
while(str[i]!='\0')
{
if(str[i]>='A'&&str[i]<='Z')
{
str[i]=str[i]+32;
}
i++;
}
printf("%s",str);
return 0;
}

//To reverse a string without string function
#include <stdio.h>
int main()
{
char str[20]="Gnana Sai";
char rev[20];
int i,j=0,l;
l=strlen(str);
for (i=l-1;i>=0;i--)
{
rev[j]=str[i];
j++;
}
rev[i]='\0';
printf("rev string:%s",rev);
return 0;
}

//To print a palindrome
#include <stdio.h>
#include <string.h>
void main()
{
char str[10]="malayalam";
int i,length,flag=0;
length=strlen(str);
for (i=0;i<length;i++)
{
if(str[i]!=str[length-i-1])
{
flag=1;
break;
}
}
if (flag==1)
{
printf("%s is not a palindrome",str);
}else{
printf("%s is a palindrome",str);
}
}

//To count no. of vowels and no. of consonants in a sentence
#include <stdio.h>
void main()
{
char sentence[30]="Gnana Sai";
int i,vowels=0;consonants=0;
char ch;
for (i=0;sentence[i]!='\0';i++)
{
ch=sentence[i];
if (ch>='a'&&ch<='z')
{
if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||)
vowels++;
else 
consonants++;
}
}
printf("no. of vowels:%d\n",vowels);
printf("no. of consonants:%d",consonants);
return 0;
}

                                                   //18-03-2026//wednesday//
#include <stdio.h>
int main()
{
  int n,i;
  int a[100];
  int max;
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  max=a[0];
  for (i=1;i<n;i++)
  {
    if (a[i]>max)
    max=a[i];
  }
  printf("%d",max);
  return 0;
}


#include <stdio.h>
int main()
{
  int i,n,a[100],min,max;
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  min=max=a[0];
  for (i=1;i<n;i++)
  {
    if(a[i]<min)
    min=a[i];
    if(a[i]>max)
    max=a[i];
  }
  printf("%d\n",min);
  printf("%d",max);
  return 0;
}

#include <stdio.h>
int main()
{
  int n,i,a[100];
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  for (i=0;i<n/2;i++)
  {
    int temp=a[i];
    a[i]=a[n-i-1];
    a[n-i-1]=temp;
  }
  for(i=0;i<n;i++)
  {
    printf("%d\n",a[i]);
  }
  return 0;
}

#include <stdio.h>
int main()
{
  int n,i,j,a[100];
  scanf("%d",&n);
  for (i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  for (i=0;i<n;i++)
  {
    for (j=i+1;j<n;j++)
    {
      if (a[i]==a[j])
      {
        printf("%d\n",a[i]);
        break;
      }
    }
  }
  return 0;
}


#include <stdio.h>
int main()
{
  int a[10][10],b[10][10],sum[10][10];
  int r,c,i,j;
  scanf("%d",&r);
  scanf("%d",&c);
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      scanf("%d",&a[i][j]);
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      scanf("%d",&b[i][j]);
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      sum[i][j]=a[i][j]+b[i][j];
    }
  }
  for (i=0;i<r;i++)
  {
    for (j=0;j<c;j++)
    {
      printf("%d ",sum[i][j]);
    }
    printf("\n");
  }
  return 0;
}


#include <stdio.h>
#include <string.h>
  int main()
  {
    char str[20]="GNANA SAI";
    char str1[20]="gnana sai";
    char str2[20]="GNANASAI";
    strlwr(str);
    strupr(str1);
    strrev(str2);
    printf("%s\n",str);
    printf("%s\n",str1);
    printf("%s",str2);
    return 0;
  }

#include <stdio.h>
struct employee
{
  char name[50];
  int empid;
  float salary;
};
int main()
{
  struct employee emp;
  scanf("%s",&emp.name);
  scanf("%d",&emp.empid);
  scanf("%f",&emp.salary);
  printf("%s\n",emp.name);
  printf("%d\n",emp.empid);
  printf("%.2f",emp.salary);
  return 0;
}


#include <stdio.h>
struct student
{
    char name[20];
    int rollno;
    float m1,m2,m3;
};
int main()
{
    struct student s;
    int avg=0;
    scanf("%s",s.name);
    scanf("%d",&s.rollno);
    scanf("%f%f%f",&s.m1,&s.m2,&s.m3);
    sum=(s.m1+s.m2+s.m3)/3.0;
    printf("%s\n",s.name);
    printf("%d\n",s.rollno);
    printf("%.2f",avg);
    return 0;
}

                                                      //19-03-2026//Thursday
//Library function
#include<srdio.h>
#include <math.h>
ingt main()
{
floar n,root,p;
scanf("%f",&n);
root=sqrt(n);
p=pow(2,3);
printf("%f",root);
printf("%f",p);
return 0;
}

//Addition of two numbers
#invlude <stdio.h>
int add(int a,int b);
int main()
{
int n1,n2,sum;
scanf("%d%d",&n1,&n2);
sum=add(n1,n2);
printf("%d",sum);
return 0;
}
int add(int a,int b)
{
int result;
result=a+b;
return result;
}

//using void function
#include <stdio.h>
void add(int a,int b);
int main()
{
int n1,n2,sum;
scanf("%d%d",&n1,&n2);
add(n1,n2);
return 0;
}
voide add(int a,int b)
{
int result;
result=a+b;
printf("%d",result);
}

//To find area of circle 
#include <stdio.h>
#define pi 3.14
float mul(r);
int main ()
{
float r,area;
scanf("%f",&r);
area=mul(r);
printf("%f",area);
return 0;
}
float mul(int r)
{
float result;
result=3.14*r*r;
return result;
}

//TO find S.I
#include <stdio.h>
float S.I(int p,intr,intt);
int main()
{
float p,t,r,S.I;
scanf("%f%f%f",&p,&t,&r);
result=S.I(p*t*r);
printf("%f",result);
return 0;
}
float S.I(int p,int t, int r)
{
float result;
result =(p*t*r)/100.0;
result result;
}

//To find area of triangle
#include <stdio.h>
float mul(int a,intb);
int main()
{
float a,b,area;
scanf("%f%f",&a,&b);
result=area(a,b);
printf("%f",result);
return 0;
}
float area(inta,intb)
{
float result;
result=0.5*a*b;
return result;
}

//To find odd or even
#include <stdio.h>
#include <stdlib.h>  // for abs()
int main() {
int num;
printf("Enter a number: ");
scanf("%d", &num);
if (abs(num) % 2 == 0)
printf("Even number");
else
printf("Odd number");
return 0;
}

// to calculate sum of first n natural numbers
#include <stdio.h>
int sum_n(int n) {
    int sum = 0;
    for(int i = 1; i <= n; i++) {
        sum += i;
    }
    return sum;
}
int main() {
int n, result;
 printf("Enter a number: ");
scanf("%d", &n);
result = sum_n(n);
printf("Sum of first %d natural numbers = %d", n, result);
return 0;
}


// To  calculate factorial using function
#include <stdio.h>
int factorial(int n) {
    int fact = 1;
    for(int i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}
int main() {
int n, result;
printf("Enter a number: ");
 scanf("%d", &n);
 result = factorial(n);
 printf("Factorial of %d = %d", n, result);
 return 0;
}


// To  find sum of digits using function
#include <stdio.h>
int sum_of_digits(int n) {
    int sum = 0;
    while(n > 0) {
        sum += n % 10;
        n = n / 10;
    }
    return sum;
}
int main() {
    int num;
printf("Enter a number: ");
scanf("%d", &num);
printf("Sum of digits = %d", sum_of_digits(num));
return 0;
}

                                                  //20-03-2026//Friday
//To find a number is palindrome
#include <stdio.h>
void pal(a);
int main()
{
int a;
scanf("%d",&a);
pal(a);
return 0;
}
void pal(int b);
{
int sum,rev=0;
b=sum;
while (sum!=0)
{
int digit=sum%10;
rev=rev*10+digit;
sum=sum/10;
}
if (b=rev)
{
printf("pal");
}else{
printf("not");
}
}

//To find perimeter of rectangle
#include <stdio.h>
int perimtr(int l,int b);
int main()
{
int l,b,y;
scanf("%d%d",&l,&b);
y=perimtr(l,b);
printf("%d",y);
return 0;
}
int perimtr(int l,int b)
{
int y;
y=2*(l+b);
return y;
}

//
