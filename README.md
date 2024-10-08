#include <stdio.h>

int main() {
    float num1 = 5.5, num2 = 7.8, num3 = 9.2; 
    float media;

   
    media = (num1 + num2 + num3) / 3;

  
    printf("Os números são: %.2f, %.2f, %.2f\n", num1, num2, num3);
    printf("A média dos três números é: %.2f\n", media);

    return 0;
}
