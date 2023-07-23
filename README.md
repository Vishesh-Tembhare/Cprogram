# Cprogram
1)WAP TO PRINT ASCII VALUE OF CHARACTER

#include <stdio.h>
char ch;
int main()
{
    printf("enter a char:\n");
    scanf("%c",&ch);
    printf("%d",ch);
    

    return 0;
}
**************************************************************************************************************************
WAP TO ACCEPT LOWECASE CHAR AMD CONVERT TO UPPERCASE

#include <stdio.h>
char ch;
int main()
{
    printf("enter lowercase char:");
    scanf("%c",&ch);
    ch=ch-32;
    printf("%c",ch);

    return 0;
}

***************************************************************************************************************************
WAP TO ACCEPT upperCASE CHAR AMD CONVERT TO lower

#include <stdio.h>
char ch;
int main()
{
    printf("enter uppercase char:");
    scanf("%c",&ch);
    ch=ch+32;
    printf("%c",ch);

    return 0;
}
***************************************************************************************************************************
SWAP TWO NO USING THIRD VARIBALE

#include <stdio.h>
int v,s,temp;
int main()
{
    printf("enter two number:\n");
    scanf("%d%d",&v,&s);
    temp=v;
    v=s;
    s=temp;
    printf("after swapping:%d %d",v,s);
    return 0;
}
*********************************************************************************************************************************
SWAP TWO NUMBER WITHOUT USING THIRD VARIABLE

#include <stdio.h>
int v,s;
int main()
{
    printf("enter two number:\n");
    scanf("%d%d",&v,&s);
    v=v+s;
    s=v-s;
    v=v-s;
    printf("after swapping:%d %d",v,s);
    return 0;
}
*********************************************************************************************************************************
swap using bitwise 

#include <stdio.h>
int x,y;
int main()
{
    printf("enter number:\n");
    scanf("%d%d",&x,&y);
    x=x^y;
    y=x^y;
    x=x^y;
    printf("after swapping:%d %d",x,y);
    return 0;
}
******************************************************************************************************************************
WAP TO FIND AREA O TRAINGLE

#include <stdio.h>
int a,h,b;
int main()
{
    printf("enter the number:\n");
    scanf("%d%d",&h,&b);
    a=(h*b)/2;
    printf("area of traingle :%d",a);

    return 0;
}
*******************************************************************************************************************************
WAP TO FINE AREA OF RECTANGLE

#include <stdio.h>
int v,a,h,b;
int main()
{
    printf("enter the number:\n");
    scanf("%d%d%d",&h,&b,&a);
    v=a*b*h;
    printf("area of rectraingle :%d",v);

    return 0;
}
********************************************************************************************************************************
WAP TO FIND AREA OF CIRCLE

#include <stdio.h>
int r,a;
int main()
{
    printf("enter the number:\n");
    scanf("%d",&r);
    a=3.14*r*r;
    printf("area of circle:%d",a);

    return 0;
}
*********************************************************************************************************************************
WAP TO FIND CIRCUMFERENCE OF CIRCLE

#include <stdio.h>
int r,a;
int main()
{
    printf("enter the number:\n");
    scanf("%d",&r);
    a=2*3.14*r*r;
    printf("circumference of circle:%d",a);

    return 0;
}
********************************************************************************************************************************
WAP TO KM TO M

#include <stdio.h>
int r,a;
int main()
{
    printf("enter the number:\n");
    scanf("%d",&r);
    a=r*1000;
    printf("km to m:%d",a);

    return 0;
}
********************************************************************************************************************************
CONVERT CELSIUS TO FARENHEIT

#include <stdio.h>
float a,f,r;
int main()
{
    printf("enter temperature in celsius:\n");
    scanf("%f",&r);
    a=1.8*r+32;
    printf("temperature in farenheit:%f",a);

    return 0;
}
********************************************************************************************************************************
WAP CONVERT FARENHEIT TO CELSIUS

#include <stdio.h>
float a,f,r;
int main()
{
    printf("enter temperature in farenheit:\n");
    scanf("%f",&r);
    a=(r-32)*5/9;
    printf("temperature in celsius:%f",a);

    return 0;
}
********************************************************************************************************************************
WAP TO FIND AVERAGE OF THREE NUMBERS

#include <stdio.h>
int a,b,c,avg;
int main()
{
    printf("enter three numbers:\n");
    scanf("%d%d%d",&a,&b,&c);
    avg=a+b+c/3;
    printf("Average of three number is :%d",avg);

    return 0;
}
********************************************************************************************************************************
WAP TO REVERSE 5 DIGIT NO WITHOUT USING LOOP

#include <stdio.h>
int r1,r2,r3,r4,r5,num,rev;
int main()
{
    printf("enter five digit number\n");
    scanf("%d",&num);
    r1=num%10;
    num=num/10;
    r2=num%10;
    num=num/10;
    r3=num%10;
    num=num/10;
    r4=num%10;
    num=num/10;
    r5=num%10;
    rev=r1*10000+r2*1000+r3*100+r4*10+r5;
    printf("reverse number is:%d",rev);
    

    return 0;
}
***************************************************************************************************************************
WAP SIMPLE INTEREST

#include <stdio.h>
int p,r,t,i;
int main()
{
    printf("enter the principle amount\n");
    scanf("%d",&p);
    printf("enter the rate\n");
    scanf("%d",&r);
    printf("enter the time\n");
    scanf("%d",&t);
    i=p*r*t/100;
    
    printf("Simple interest is :%d",i);
    

    return 0;
}
****************************************************************************************************************************
WAP TO COMPOUND INTEREST

#include <stdio.h>
#include <math.h>

float p,r,t,i;
int main()
{
    printf("enter the principle amount\n");
    scanf("%f",&p);
    printf("enter the rate\n");
    scanf("%f",&r);
    printf("enter the time\n");
    scanf("%f",&t);
    i= p* (pow((1+r/100),t));
    
    
    printf("compound interest is :%f",i);
    

    return 0;
}
***************************************************************************************************************************************
WAP ACCEPT CHARACTER AND CONVERT INTO OPPOSITE

char ch,c,i;
int main()
{
    printf("enter a character:\n");
    scanf("%c",&ch);
    if (ch >= 'a' && ch <='z')
    {
        ch=ch-32;
    }
        else
        {
            ch=ch+32;
        }
    
    printf("opposite case:%c",ch);

    return 0;
}
**************************************************************************************************************************************
WAP ACCEPT CHARACTER AND CHECK IT IS LOWERCASE OE UPPER CASE

#include <stdio.h>
char ch,c;
int main()
{
    printf("enter a character:\n");
    scanf("%c",&ch);
    if (ch >= 'A' && ch <='Z')
    {
        printf("'%c'is uppercase",ch);
        
    }
        else if(ch>='a'&& ch<='z')
        {
             printf("'%c'is lowercase",ch);
        }
        else
        {
           printf("'%c'is not alphabhet",ch);

        }

    return 0;
}
************************************************************************************************************************************
WAP TO ACCEPT CHAR AND DIGIT OR CHARACTER OR SYMBOL

#include <stdio.h>
char ch,c;
int main()
{
    printf("enter the characte:\n");
    scanf("%c",&ch);
    if (ch>=65 && ch<=90 || ch>=97 && ch<=122)
    {
        printf("character is alphabet");
    }
    else if (ch>=48 && ch<=58)
    {
        printf("it is a number");
    }
    else
    {
        printf("it is special symbol");
    }

    return 0;
}
************************************************************************************************************************************
WAP CONSTANT OR VOWELS                                           

#include <stdio.h>
char c;
int uppercase,lowercase;
int main()
{
    printf("enter the character:\n");
    scanf("%c",&c);
    lowercase=(c== 'a' || c=='e' || c=='i' || c=='o' || c=='u');
    uppercase=(c=='A' || c=='E' || c=='I' || c=='O' || c=='U');
    if (lowercase || uppercase){
        printf("it is vowels");
    }
    else{
        printf("it is consatant");
    }
    return 0;
}



#include <stdio.h>
char ch;
int main()
{
    
    printf("enter the character:\n");
    scanf("%c",&ch);
    switch(ch)
    {
        case 'a':
        printf("it is vowel");
        break;
        
        case 'e':
        printf("it is vowel");
        break;
        
        case 'i':
        printf("it is vowel");
        break;
        
        case 'o':
        printf("it is vowel");
        break;
        
        case 'u':
        printf("it is vowel");
        break;
        
        default:
        printf("it is consatnt");
    }
    return 0;
}
**********************************************************************************************************************************
WAP EVEN OR ODD

#include <stdio.h>
int n;
int main()
{
    printf("enter a number:\n");
    scanf("%d",&n);
    if(n %2 ==0){
        printf("it is even number");
    
    }
    else{
        printf("it is odd number");
    }
    
    return 0;
}
********************************************************************************************************************************
WAP TO CHECK +VE OR -VE

#include <stdio.h>
int n;
int main()
{
    printf("enter a number:\n");
    scanf("%d",&n);
    if(n==0)
    {
        printf("niether +ve nor negative");
    
    }
    else if (n<0)
    {
        printf("it is negative number");
    }
    else{
        printf("it is positive number");
    }
    
    return 0;
}
***********************************************************************************************************************************
WAP ACCEPT YEAR AND CHECK LEAP YEAR OR  NOT

#include <stdio.h>
int year;
int main()
{
    printf("enter a year:\n");
    scanf("%d",&year);
    if((year % 4 ==0)|| (year % 100==0) || (year % 400==0))
    {
        printf("The year is leap year");
    }
    else
    {
        printf("it is not leap year");
    }

    return 0;
}
**********************************************************************************************************************************
WAP ACCEPT TWO NUMBER AND PRINT MAX

#include <stdio.h>
int v,s;
int main()
{
    printf("enter a first number\n");
    scanf("%d",&v);
    printf("enter a second number\n");
    scanf("%d",&s);
    if (v>s)
    {
        printf("Max number is:%d",v);
    }
    else
    {
        printf("the is not max");
    }

    return 0;
}
********************************************************************************************************************************
WAP ACCEPT THREE NUMBER AND PRINT MAX

#include <stdio.h>
int v,s,t;
int main()
{
    printf("enter a first number\n");
    scanf("%d",&v);
    printf("enter a second number\n");
    scanf("%d",&s);
    printf("enter a third number\n");
    scanf("%d",&t);
    if (v>= s && v>=t)
    {
        printf("Max number is:%d",v);
    }
    else if (s>=v && s>=t)
    {
        printf("Max number is:%d",s);
    }
    else if (t>=v && t>=s)
    {    
      printf("Max number is:%d",t);
    }
    return 0;
}
************************************************************************************************************************************
WAP ACCEPT THREE NUMBER AND PRINT MINIMUM

#include <stdio.h>
int v,s,t;
int main()
{
    printf("enter a first number\n");
    scanf("%d",&v);
    printf("enter a second number\n");
    scanf("%d",&s);
    printf("enter a third number\n");
    scanf("%d",&t);
    if (v<= s && v<=t)
    {
        printf("MINIMUM number is:%d",v);
    }
    else if (s<=v && s<=t)
    {
        printf("MINIMUM number is:%d",s);
    }
    else if (t<=v && t<=s)
    {    
      printf("MINIMUM number is:%d",t);
    }
    return 0;
}
************************************************************************************************************************************
WAP TO PRINT FIRST 10 EVEN NUMBER

#include <stdio.h>
int n,i;
int main()
{
    printf("first 10 even number are:\n");
    for(i=0;i<=10;i++)
    {
        printf("%d\n",2*i);
    }

    return 0;
}
*************************************************************************************************************************************
WAP TO PRINT FIRST 10 ODD NUMBER

#include <stdio.h>
int n,i;
int main()
{
    printf("first 10 even number are:\n");
    for(i=0;i<=10;i++)
    {
        printf("%d\n",2*i-1);
    }

    return 0;
}
**************************************************************************************************************************************
WAP TO PRINT DIVISOR OF NUMBER

#include <stdio.h>
int v,i;
int main()
{
    printf("enter the interger:\n");
    scanf("%d",&v);
    printf("divisor of the given number is:%d\n",v);
    for(i=1;i<=v;i++){
        if((v%i)==0){
            printf("%d\n",i);
            printf("\n");
        }
    }

    return 0;
}
*******************************************************************************************************************************
WAP TO CHECK NUMBER IS PERFECT NUMBER OR NOT

#include<stdio.h>  
#include<conio.h>  
void main()  
{  
int i = 1, num, Sum = 0;  
printf(" Enter the Number \n");  
scanf("%d", &num);  
  
while(i < num )  
                     {  
                               if(num % i == 0)  
                               Sum = Sum + i;  
                               i++;  
                     }  
           if(Sum == num)  
                  printf("\n %d is Perfect Number", num);  
           else  
           printf("\n %d is not a Perfect Number", num);  
getch();  
}
******************************************************************************************************************************
WAP CHECK PALLINDROME

#include<stdio.h>  
int main()    
{    
int n,r,sum=0,t;    
printf("enter the number=");    
scanf("%d",&n);    
t=n;    
while(n>0)    
{    
r=n%10;    
sum=(sum*10)+r;    
n=n/10;    
}    
if(t==sum)    
printf("palindrome number ");    
else    
printf("not palindrome");   
return 0;  
}  
*******************************************************************************************************************************
WAP TO REVERSE NUMBER

#include<stdio.h>  
 int main()    
{    
int n, rev=0, rem;    
printf("Enter a number: ");    
  scanf("%d", &n);    
  while(n!=0)    
  {    
     rem=n%10;    
     reVe=rev*10+rem;    
     n/=10;    
  }    
  printf("Reversed Number: %d",rev);    
return 0;  
}  
******************************************************************************************************************************** 
WAP TO CHECK ARMSTRONG OR NOT

#include<stdio.h>  
 int main()    
{    
int n,r,sum;    
printf("Enter a number: ");    
  scanf("%d", &n);
while(n>0)
{
 r=n%10;
sum=sum+(r*r*r);
n=n/10;
}
if(n==sum)
{
printf("it is armstrong number");
}
else
{
printf("it is not a aramstrong number");
}
return 0;
}
************************************************************************************************************************************









