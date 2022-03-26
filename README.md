# ADD-DIGIT-OF-A-NUMBER

#include <stdio.h>

int adddigit(int num)
{
    int i;
    while(num/10>0)
    i=num;
    num=0;
    while(i>0)
    {
        num=num+(i%10);
        i=i%10;
    }

    return 0;
}
