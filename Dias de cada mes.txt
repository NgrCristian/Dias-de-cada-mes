#include <stdio.h>

main(){
    int n;

    printf("Escolha o mes(de 0 a 12)");
    scanf("%d", &n);

    switch (n)
    {
    case 1:
        printf("31 dias");
        break;
    case 2:
        printf("28 ou 29 dias");
        break;
    case 3:
        printf("31 dias");
        break;
    case 4:
        printf("30 dias");
        break;
    case 5:
        printf("31 dias");
        break;
    case 6:
        printf("30 dias");
        break;
    case 7:
        printf("31 dias");
        break;
    case 8:
        printf("31 dias");
        break;
     case 9:
        printf("30 dias");
        break;
    case 10:
        printf("31 dias");
        break;
    case 11:
        printf("30 dias");
        break;
    case 12:
        printf("31 dias");
        break;

    default:
        printf("invalido");
        break;
    }

    return 0;
}
