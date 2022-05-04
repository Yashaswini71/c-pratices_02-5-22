/*Write a C program to check whether a string is palindrome or not. */

#include<stdio.h>
#include<string.h>

int palindrome(char *s);

int main()
{
        char s[100];
        printf("Enter the string:");
        scanf("%[^\n]%*c",s);
        if(palindrome(s))
                printf("String is palindrome\n");
        else
                printf("String is not pailndrome\n");
        return 0;
}

int palindrome(char *s)
{
        int i,c=0,n;
        n=strlen(s);
        for(i=0;i<n/2;i++)
        {
                if(s[i]==s[n-i-1])
                        c++;
        }
        if(c==i)
                return 1;
        else
                return 0;
}
