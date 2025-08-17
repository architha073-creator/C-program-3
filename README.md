# C-program-3
Temperature
#include<stdio.h>
int main()
{
    float temp,celcius;
    printf("Enter temp");
    scanf("%f",& temp);
    if (temp>80)
    {
        celcius = (temp-32)*(5.0/9);
        printf("celcius=%.2f\n",celcius);
    }
    else
    {
        celcius = temp;
    }  
    if (celcius>30) 
    {
        printf("Hot");
    }
    else if (celcius>=20 && celcius<=30)
    {
        printf("medium");
    }
    else
    {
        printf("cold");
    }
    return 0 ;
    }
