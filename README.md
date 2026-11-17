#include<stdio.h>
#include<stdlib.h>

int main()
{
float phone_time, pooptime, eat_time;
float total,average ;
printf("Enter your phone_time in minutes:");
scanf("%f",&phone_time);

printf("Enter your pooptime in minutes:");
scanf("%f",&pooptime);

printf("Enter your eat_time in minutes:");
scanf("%f",&eat_time);

total = phone_time + pooptime+ eat_time;
average = total/3;

printf("\n Total time spent = %.2f.minutes",total);
printf("\n Average time spent= %.2f.minutes",average);

return 0;
}



