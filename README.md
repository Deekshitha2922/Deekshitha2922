#include <stdio.h>
#include<string.h>
void main()
{

    char a[200];
    printf("Enter the sentence");
    gets(a);
    int len=strlen(a);
    int count=0;
    for(int i=0;i<len;i++)
    {
        if(a[i]==' ')
        count=count+1;
    }
    printf("The number of words is %d",count+1);
}

