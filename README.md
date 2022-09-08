# 2-D-string
This is a program for multidimensional strings in C programming.


#include <stdio.h>
int main()
{
    char s[3][10];
    printf("Enter three strings:");
    int i;
    for (i = 0; i < 3; i++)
    {
        gets(&s[i][0]);
    }
    for (i = 0; i < 3; i++)
    {
        printf("%s\n", s[i]);
    }

    return 0;
}
