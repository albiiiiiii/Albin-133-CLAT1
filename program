#include <stdio.h>

int main()
{
    float temperature,solution;
    char unit;
    printf("Welcome to the temperature calculator\n");
    printf("Enter the type of temperature whether fahrenheit or celcius (f/c):"); 
    scanf("%s",&unit);
    if(unit=='f' || unit=='F')
    {
        printf("enter temperature in fahrenheit:");
        scanf(" %f",&temperature);
        solution=(temperature-32)*5/9;
        printf("The temperature in celcius is: %.2f",solution);
    }
    else if(unit=='c' || unit=='C')
    {
        printf("Enter the temperature in celcius:");
        scanf(" %f",&temperature);
        solution=(temperature+32)*1.8;
        printf("The temperature in fahrenheit is: %.2f",solution);
    }
    else
    {
        printf("Invalid choice");
    }
    return 0;
}
