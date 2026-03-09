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
