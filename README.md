# Trabalho de Programação
Atividade de Conclusão do 4° Bimestre
2° ano "A" - TDS - Isabel Emanuelly Ferreira Rodrigues (n° 13)
Utilizarei a linguagem C para responder os desafios.

Desafio 1
#include <stdio.h>

int main() {
    printf("Hello world!\n");
    return 0;
}

Desafio 2
#include <stdio.h>

int main() {
     int n1=78, n2=456, soma;
    soma = n1 + n2;

    printf("A soma é: %d \n", soma);
    return 0;
}

Desafio 3
 #include <stdio.h>

int main() {
    int n1=-987, n2=1456, soma, sub, mult;
    soma = n1 + n2;
    sub = n1 - n2;
    mult = n1 * n2;
    
    printf("A soma é: %d \n", soma);
    printf("A subtração é: %d \n", sub);
    printf("A multiplicação é: %d", mult);
    return 0;
}

Desafio 4
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

Desafio 5
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

Desafio 6
#include <stdio.h>

int main() {
    float n1=18, n2=-4, div;
    div = n1 / n2;

    printf("A divisão é: %f", div);
    return 0;
}

Desafio 7
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

Desafio 8
 #include <stdio.h>

int main() {
    float pi=3.14, r=5, area, comp;
    area = pi * (r*r);
    comp = 2 * pi *r;
    
    printf("A area é: %f \n", area);
    printf("O comprimento é: %f", comp);
    return 0;
}

Desafio 9
 #include <stdio.h>

int main() {
    float pi=3.14, r=3, vol;
    vol = (4 * pi * (r*r*r))/3;
    
    printf("O volume é: %f", vol);
    return 0;
}

Desafio 10
 #include <stdio.h>

int main() {
    float B=10, b=7, h=4, area;
    area = ((B+b)*h)/2;
    
    printf("A área é: %f", area);
    return 0;
}

Desafio 11
 #include <stdio.h>

int main() {
    float C=22, F;
    F = (C * 9/5) + 32;
    
    printf("A temperatua em Fahrenheit é: %f", F);
    return 0;
}

Desafio 12
 #include <stdio.h>

int main() {
    float F=93;
    float C = (15/9.0) * (F−32);
    
    printf("A temperatura em Celsius é: %f", C);
    return 0;
}

Desafio 13
 #include <stdio.h>

int main() {
    int A=8, B=13, C=21;
    int soma = (A*A) + (B*B) + (C*C);
    
    printf("A soma do quadrado dos numeros 8,13 e 21 é: %d", soma);
    return 0;
}

Desafio 14
 #include <stdio.h>

int main() {
    int A=4, B=7, C=19;
    int soma = A + B + C;
    int qua = soma * soma;
    
    printf("A quadrado da soma dos numeros 4, 7 e 19 é: %d", qua);
    return 0;
}

Desafio 15
 #include <stdio.h>

int main() {
    float km=208, l=18;
    float cons = km / l;
    
    printf("O consumo é de: %f km/l \n", cons);
    return 0;
}
