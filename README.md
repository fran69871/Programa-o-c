
#include <stdio.h>  


int main()
    
 {
    int: carta 1, carta 2;
    char estado(A,B);        
    char codigo[3](A01,B02)     
    char nome Cidade[30]; 
    int populacao;      
    float area;         
    float pib;         
    int pontos Turisticos; 
 }

 {
    printf("Digite a letra do estado (A ou B):\n ");
    scanf(" %c", &estado);
    printf("Digite o código da carta (Ex: A01, B02):\n ");
    scanf("%s", &codigo);
    printf("Digite o nome da cidade:\n ");
    scanf(" %c", &Cidade);
    printf("Digite a população:\n");
    scanf("%d", &populacao);
    printf("Digite a área em km²:\n");
    scanf("%f", &area);
    printf("Digite o PIB da cidade:\n ");
    scanf("%f", &pib);
    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontosTuristicos);
}


{
    
    printf("Estado: %c\n", carta.estado);
    printf("Código da carta: %s\n", carta.codigo);
    printf("Nome da cidade: %s\n", carta.nomeCidade);
    printf("População: %d habitantes\n", carta.populacao);
    printf("Área: %.2f km²\n", carta.area);
    printf("PIB: %.2f bilhões\n", carta.pib);
    printf("Pontos turísticos: %d\n", carta.pontosTuristicos);
   
}

int main() {
    int: Carta carta1, carta2;

   
    printf("Insira os dados da primeira carta:\n");
    inserirCarta(&carta1);
    printf("Insira os dados da segunda carta:\n");
    inserirCarta(&carta2);

    
    printf("Cartas cadastradas:\n");
    exibirCarta(carta1);
    exibirCarta(carta2);

    return 0;
}