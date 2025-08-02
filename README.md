# count-digit-C
#include<stdio.h> <Br>
int main() <Br>
{ <Br>
int n;<Br>
printf("Enter a number");<Br>
scanf("%d",&n);<Br>
int count=0;<Br>
while (n>0)<Br>
{<Br>
n=n/10;<Br>
count++;<Br>
}<Br>
printf("count of digits is %d:",count);<Br>
}<Br>
