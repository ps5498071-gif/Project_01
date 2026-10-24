# Project_01

#include <stdio.h>
int main(){ 
    printf("Bem-vindo a linguagem C \n\n");
int idade; 
printf("Digite sua idade: ");
scanf("%d", &idade);

float altura; 
printf("Digite sua altura: ");
scanf("%f", &altura);

float nota;
printf("Digite sua nota: "); 
scanf("%f", &nota); 

printf("\nExibindo as informações \n");
printf("Idade: %d anos, altura: %.2f, nota: %1.f", idade,altura,nota);

return 0;
}