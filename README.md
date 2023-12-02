# Trabalho de Programação
Atividade de Conclusão do 4° Bimestre
2° ano "A" - TDS - Isabel Emanuelly Ferreira Rodrigues (n° 13)
Utilizarei a linguagem C para responder os desafios.

Desafio 1
 #include <stdio.h>

int main() {
    int n1=9, n2=5, n3=6, soma, sub, mult;
    soma = n1 + n2 + n3;
    sub = n1 - n2 - n3;
    mult = n1 * n2 * n3;
    
    printf("A soma é: %d \n", soma);
    printf("A subtração é: %d \n", sub);
    printf("A multiplicação é: %d", mult);
    return 0;
}

Desafio 2
 #include <stdio.h>

int main() {
    float n1=8.5, n2=6.8, soma, sub, mult, div;
    soma = n1 + n2;
    sub = n1 - n2;
    mult = n1 * n2;
    div = n1 / n2;
    
    printf("A soma é: %f \n", soma);
    printf("A subtração é: %f \n", sub);
    printf("A multiplicação é: %f \n", mult);
    printf("A divisão é: %f", div);
    return 0;
}

Desafio 3
#include <stdio.h>

int main() {
    float n1=18, n2=-4, div;
    div = n1 / n2;

    printf("A divisão é: %f", div);
    return 0;
}

Desafio 4
 #include <stdio.h>

int main() {
    float n1=11.3, n2=3.9, n3=27, soma, sub, mult, div;
    soma = n1 + n2 + n3;
    sub = n1 - n2 - n3;
    mult = n1 * n2 * n3;
    div = n1 / n2 / n3;
    
    printf("A soma é: %f \n", soma);
    printf("A subtração é: %f \n", sub);
    printf("A multiplicação é: %f \n", mult);
    printf("A divisão é: %f", div);
    return 0;
}

Desafio 5
 #include <stdio.h>

int main() {
    float pi=3.14, r=5, area, comp;
    area = pi * (r*r);
    comp = 2 * pi *r;
    
    printf("A area é: %f \n", area);
    printf("O comprimento é: %f \n", comp);
    return 0;
}

Desafio 6
 #include <stdio.h>

int main() {
    float pi=3.14, r=3, vol;
    vol = (4 * pi * (r*r*r))/3;
    
    printf("O volume é: %f \n", vol);
    return 0;
}

Desafio 7
 #include <stdio.h>

int main() {
    float B=10, b=7, h=4, area;
    area = ((B+b)*h)/2;
    
    printf("A área é: %f \n", area);
    return 0;
}

Desafio 8
 #include <stdio.h>

int main() {
    float C=22, F;
    F = (C * 9/5) + 32;
    
    printf("A temperatua em Fahrenheit é: %f \n", F);
    return 0;
}

Desafio 9
