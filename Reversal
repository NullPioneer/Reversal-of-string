#include <stdio.h>
#include <string.h>
char s[50];
int top=-1, maxsize=50;
int push(int val)
{
if (top == maxsize -1) 
{
printf("stack overflow\n");
} 
else 
{
 top++;
 s[top] = val;
}
}
void display()
{
if (top==-1)
{
printf("stack is empty\n");
} 
else 
{
printf("Reversed string is: ");
for(int i=0;i<= top;i++) 
{
printf("%d",s[i]);
}
}
}
void main()
{
    int i,val,len;
    printf("Enter a string");
    scanf("%d",&s);
    printf("Enter the length");
    len=strlen(s);
    printf("%d",len);
    for(i=0;i<=len;i++)
    {
       push(s[i]);
    }
}
