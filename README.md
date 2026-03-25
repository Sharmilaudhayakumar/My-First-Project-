# My-First-Project-
Student grade Calculator Program 

#include<stdio.h>
int main()
{
int s1,s2,s3;
float avg;
scanf("%d%d%d",&s1,&s2,&s3);
avg=(s1+s2+s3)/3;
if(s1>=0&&s1<=100&&s2>=0&&s2<=100&&s3>=0&&s3<=100)
{
if(s1<35||s2<35||s3<35)
printf("Fail");
else
if(avg>=90)
printf("A+");
else if(avg>=75)
printf("A");
else if(avg>=50)
printf("B");
else
printf("C");
}
else
printf("Invalid mark");
return 0;
} 
