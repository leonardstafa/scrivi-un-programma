/*Scrivi un programma*/
#include <stdio.h>

int main() {
    char nome[50];

    printf("Inserisci il tuo nome: ");
    scanf("%s", nome);

    printf("Buongiorno, %s!\n", nome);

    return 0;
}
