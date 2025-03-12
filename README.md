# c-15
String comparing
#include<stdio.h>
#include<string.h>
int main()
{
    char s1[20]="Mississippi";
    char s2[20]="Mississippi";
    char s3[20]="Mississippi";
    printf("%d",strcmp(s1,s2));
    printf("%d",strcmp(s2,s3));
    return 0;
}
