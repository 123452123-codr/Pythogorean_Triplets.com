# Pythogorean-triplets
A C++ program to check whether three numbers are Pythogorean triplets or not... Useful for several mathematical calculations...

Source code : 


#include<iostream.h>
<br>
#include<conio.h>
<br>
void main()
<br>
{
<br>
clrscr();
<br>
long int a,b,c;
<br>
cout<<"Enter the value of three sides:";
<br>
cin>>a>>b>>c;
<br>
if(a >= b+c || b >= a+c || c >= a+b)
<br>
{
<br>
cout<<"Error! Invalid input!";
<br>
else
<br>
{
<br>
if(a>b && a>c)
<br>
{
<br>
if(a*a == b*b+c*c)
<br>
cout<<"Yes";
<br>
else
<br>
cout<<"No";
<br>
}
<br>
else if(b>a && b>c)
<br>
{
<br>
if(a*a == b*b+c*c)
<br>
cout<<"Yes";
<br>
else
<br>
cout<<"No";
<br>
}
<br>
else
<br>
{
<br>
if(a*a == b*b+c*c)
<br>
cout<<"Yes";
<br>
else
<br>
cout<<"No";
<br>
}
<br>
}
<br>
}
<br>
getch();
<br>
}
