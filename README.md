write a program to print the perfect subset from the starting point of the string example input missisipi out put miss starting
#include <stdio.h>
#include<string.h>
int main()
{
   
   char str[100], sstr[100];
   
   int i=0,n;
   printf("\n enter the string");
   scanf("%s",str);
   printf("\n enter the no of char to copy");
   scanf("%d",&n);
   i=0;
   while (str[i] !='\0' && i<n)
   {
       sstr[i] = str[i];
       i++;
   }
   sstr[i]='\0';
   printf("the substring is:");
   puts(sstr);
   return 0;
}
