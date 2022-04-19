# satya
#include <stdio.h>

int main() {
    float totalkm,meters,feet,inches,centimeters;
    scanf("%f",&totalkm);
    meters = totalkm*1000;
    feet = totalkm*3280.84;
    inches = totalkm*39370.1;
    centimeters = totalkm*100000;
    printf("%.2f m\n",meters);
    printf("%.2f ft\n",feet);
    printf("%.2f in\n",inches);
    printf("%.2f cm",centimeters);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
