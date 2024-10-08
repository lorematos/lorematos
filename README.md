#include <stdio.h>

int main() {
    float num1 = 5.2, num2 = 7.5, num3 = 9.5; // Números já definidos
    float media;

    // Calcula a média
    media = (num1 + num2 + num3) / 3;

    // Exibe os números e a média
    printf("Os números são: %.2f, %.2f, %.2f\n", num1, num2, num3);
    printf("A média dos três números é: %.2f\n", media);

    return 0;
}

