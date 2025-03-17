#include <stdio.h>

// Definição da estrutura para armazenar os dados da carta
struct Carta {
    char carta[50];           // Nome ou identificação da carta
    char estado[50];          // Estado da cidade
    char codigo[50];          // Código identificador da carta
    char nomeCidade[50];      // Nome da cidade
    long int populacao;       // População da cidade
    float areaKm2;            // Área da cidade em Km²
    long int pib;             // PIB da cidade
    int pontosTuristicos;     // Número de pontos turísticos
};

// Função para limpar o buffer de entrada
void limparBuffer() {
    int c;
    while ((c = getchar()) != '\n' && c != EOF);
}

int main() {
    
    // Declaração de duas cartas
    struct Carta carta1, carta2;

    // Inserindo os dados da primeira carta
    printf("Insira os dados da primeira carta:\n");

    printf("Carta: "); //1
    scanf(" %49[^\n]", carta1.carta);
    limparBuffer(); // Limpa buffer

    printf("Estado: "); //Amazonas
    scanf(" %49[^\n]", carta1.estado);
    limparBuffer();

    printf("Código da carta: "); //A01
    scanf(" %49[^\n]", carta1.codigo);
    limparBuffer();

    printf("Nome da cidade: "); //Tefé
    scanf(" %49[^\n]", carta1.nomeCidade);
    limparBuffer();

    printf("População: "); //59.250
    scanf("%ld", &carta1.populacao);
    limparBuffer();

    printf("Área (em Km²): "); //23.704,426
    scanf("%f", &carta1.areaKm2);
    limparBuffer();

    printf("PIB: "); //934.210.620,00
    scanf("%ld", &carta1.pib);
    limparBuffer();

    printf("Número de pontos turísticos: "); //5
    scanf("%d", &carta1.pontosTuristicos);
    limparBuffer();


    printf("\nInsira os dados da segunda carta:\n");

    printf("Carta: "); //2
    scanf(" %49[^\n]", carta2.carta);
    limparBuffer();

    printf("Estado: "); //Bahia
    scanf(" %49[^\n]", carta2.estado);
    limparBuffer();

    printf("Código da carta: "); //A02
    scanf(" %49[^\n]", &carta2.codigo);
    limparBuffer();

    printf("Nome da cidade: "); //Salvador
    scanf(" %49[^\n]", carta2.nomeCidade);
    limparBuffer();

    printf("População: "); //2.900.319
    scanf("%ld", &carta2.populacao);
    limparBuffer();

    printf("Área (em Km²): "); //692,818
    scanf("%f", &carta2.areaKm2);
    limparBuffer();

    printf("PIB: "); //63,8 BI
    scanf("%ld", &carta2.pib);
    limparBuffer();

    printf("Número de pontos turísticos: "); //5
    scanf("%d", &carta2.pontosTuristicos);
    limparBuffer();

    // Exibindo os dados inseridos
    printf("\nDados da primeira carta:\n");
    printf("Carta: %s\n", carta1.carta);
    printf("Estado: %s\n", carta1.estado);
    printf("Código da carta: %s\n", carta1.codigo);
    printf("Nome da cidade: %s\n", carta1.nomeCidade);
    printf("População: %ld\n", carta1.populacao);
    printf("Área: %.0f Km²\n", carta1.areaKm2);
    printf("PIB: %.ld Reais\n", carta1.pib);
    printf("Número de pontos turísticos: %d\n", carta1.pontosTuristicos);

    printf("\nDados da segunda carta:\n");
    printf("Carta: %s\n", carta2.carta);
    printf("Estado: %s\n", carta2.estado);
    printf("Código da carta: %s\n", carta2.codigo);
    printf("Nome da cidade: %s\n", carta2.nomeCidade);
    printf("População: %ld\n", carta2.populacao);
    printf("Área: %.0f Km²\n", carta2.areaKm2);
    printf("PIB: %ld Reais\n", carta2.pib);
    printf("Número de pontos turísticos: %d\n", carta2.pontosTuristicos);

    return 0;
}
