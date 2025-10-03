#include <stdio.h>

int main()
{
    float sensor1, sensor2, sum;
    printf("Enter the temperature of sensor 1:\n");
    scanf("%f", &sensor1);
    printf("Enter the temperature of sensor 2:\n");
    scanf("%f", &sensor2);
    sum = sensor1 + sensor2;
    printf("Total temp of sensors: %f\n", sum);
    return 0;
    
}

