//Thiago kovalczuk
//data inicio:09/09/26
//data fim:09/09/2026
//Triagem foda-se
#include <stdio.h>

int main() {

    int idade;
    int cod_gravidade;
   
    printf("Qual a idade do paciente? ");
    scanf("%d", &idade);
   
    printf("Qual o cod_gravidade do paciente (1, 2 ou 3)? ");
    scanf("%d", &cod_gravidade);
       
    if (idade < 12) {
        printf("Encaminhar para a pediatria\n");
    }
    else if (idade > 60) {
        printf("Encaminhar para geriatria\n");
    }  
    else {
        printf("Encaminhar para clinica geral\n");
    }
   
    if (cod_gravidade == 1) {
        printf("Prioridade: emergência\n");
    }    
    else if (cod_gravidade == 2) {
        printf("Prioridade: urgência\n");
    }    
    else {
        printf("Prioridade: eletivo\n");
    }
   
    return 0;
}
