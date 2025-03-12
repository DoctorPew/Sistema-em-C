#include <stdio.h>
#include <math.h>
#include <locale.h>
#include <stdlib.h>

int main() {
    int A;
    double S; // número 1 de cálculo
    double D; // número 2 de cálculo
    float F;  // variável de operação
    float senha;
    int tentativas = 3;
    int menu1; // variável menu principal
    int menu2; // variável para menus secundários
    int acertos = 0; // variável de questões
    // variáveis média aritmética
    int contador = 0;
    float M;
    // variáveis IMC
    int i;
    float massa, altura, imc;
    // variaveis segundo grau
    float a,b,c,delta;
    float x1, x2;

  do { // sistema de senha
        printf("\nDigite a senha:\n");
        scanf("%f", &senha);
        fflush(stdin);
       
        if (senha != 10) {
            tentativas--;
         printf("Senha incorreta, tente novamente.\n");

        }
        if(tentativas <= 0){
            printf("Tentativas esgotadas\n");
            printf("\nSaindo do programa...\n");
            return 0;
       }

    } while (senha != 10);
    

    printf("\nSenha correta!\n\n");
     printf("\nInicianto sistemas\n");


    while (1) { // Loop principal (menu principal)
       printf("\nx--------------------------------Sistema----------------------------------------x\n");
       printf("V 0.0.2\n");
        printf("\n\nBem vindo ao sistema, qual operação deseja utilizar hoje?\n");
        printf("\n-1 para calculadora completa.\n");
        printf("-2 para questoes matematicas.\n");
        printf("-3 para sair.\n");
   

        scanf("%d", &menu1);
        fflush(stdin);

        if (menu1 == 1) {
            while (1) { // Loop da calculadora
                printf("\nBom dia! Bem vindo a calculadora!\n"); // menu calculadora
                printf("#-----------------------#");
                printf("\n-1 para soma.\n");
                printf("-2 para subtrair.\n");
                printf("-3 para dividir.\n");
                printf("-4 para multiplicar.\n");
                printf("-5 para raiz quadrada.\n");
                printf("-6 para potenciação.\n");
                printf("-7 para seno.\n");
                printf("-8 para cosseno.\n");
                printf("-9 para tangente.\n");
                printf("-10 para média aritimetica de 5 números.\n");
                printf("-11 para calcular seu IMC.\n");
                printf("-12 para calcular equações de segundo grau\n");
                printf("#-----------------------#");
                printf("\nDigite um número:\n");
                scanf("%d", &A);
                fflush(stdin);

                switch (A) { // calculadora opções
                    case 1:
                        printf("Você selecionou somatoria.\n\n\a");
                        printf("Digite os números para soma, ponha espaço entre eles.\n");
                        scanf("%lf%lf", &S, &D);

                        F = S + D;

                        printf("O resultado da operação é: %.2f\n\a", F);
                        break;

                    case 2:
                        printf("Você selecionou subtração.\n\n\a");
                        printf("Digite os números para subtrair, ponha espaço entre eles.\n");
                        scanf("%lf%lf", &S, &D);

                        F = S - D;

                        printf("O resultado da operação é: %.2f\n\a", F);
                        break;

                    case 3:
                        printf("Você selecionou divisão.\n\n\a");
                        printf("Digite os números para dividir, ponha espaço entre eles.\n");
                        scanf("%lf%lf", &S, &D);

                        F = S / D;

                        printf("O resultado da operação é: %.2f\n\a", F);
                        break;

                    case 4:
                        printf("Você selecionou multiplicação.\n\n\a");
                        printf("Digite os números para multiplicar, ponha espaço entre eles.\n");
                        scanf("%lf%lf", &S, &D);

                        F = S * D;

                        printf("O resultado da operação é: %.2f\n\a", F);
                        break;

                    case 5:
                        printf("Você selecionou raiz quadrada.\n\n\a");
                        printf("Digite o número para calcular a raiz quadrada.\n");
                        scanf("%lf", &S);

                        printf("A raiz quadrada de %.2f é %.2f\n\a", S, sqrt(S));
                        break;

                    case 6:
                        printf("Você escolheu potenciação.\n\n\a");
                        printf("Digite os dois números um para ser a base e o outro para ser expoente.\n");
                        scanf("%lf%lf", &S, &D);

                        printf("%.2f elevado a %.2f é igual a %.2f\n\a", S, D, pow(S, D));
                        break;

                    case 7:
                        printf("Você escolheu calcular o seno de um ângulo.\n\n\a");
                        printf("Digite o ângulo que quer o seno:\n");
                        scanf("%lf", &S);

                        printf("O seno de %.2f graus é %.2f\n\a", S, sin(S * M_PI / 180.0));
                        break;

                    case 8:
                        printf("Você escolheu calcular o cosseno de um ângulo.\n\n\a");
                        printf("Digite o ângulo que quer o cosseno:\n");
                        scanf("%lf", &S);

                        printf("O cosseno de %.2f graus é %.2f\n\a", S, cos(S * M_PI / 180.0));
                        break;

                    case 9:
                        printf("Você escolheu calcular a tangente de um ângulo.\n\n\a");
                        printf("Digite o ângulo que quer a tangente:\n");
                        scanf("%lf", &S);

                        printf("A tangente de %.2f graus é %.2f\n\a", S, tan(S * M_PI / 180.0));
                        break;

                    case 10:
                        printf("Você escolheu calcular a média aritmética.\n\n\a");

                    


                     int i = 0;
                     float soma = 0, temp, media;
                      int counter = 0;
                     while(1)
                    {
                      printf("Insira o numero %i: ", counter);
                      if(!scanf("%f", &temp))
                      {
                      media = soma / (float)counter;
                       printf("Media: %.2f\n", media);
                       return 1;
                      break;
                    }
                      soma += temp;
                      counter++;
                     }
                    
                     break;


                       

                    case 11:
                        printf("\nVocê selecionou calcular o IMC\n");

                        printf("Digite o peso:\n");
                        scanf("%f", &massa);
                        fflush(stdin);

                        printf("Digite a altura:\n");
                        scanf("%f", &altura);
                        fflush(stdin);

                        imc = massa / (altura * altura);

                        printf("\nSeu IMC é de: %.2f kg/m2\n", imc);
                        break;

                    case 12:
                        printf("Você selecionou calcular equações de segundo grau.\n");
                        printf("Digite o valor de A:\n");
                        scanf("%f", &a);

                        printf("Digite o valor de B:\n");
                        scanf("%f", &b);

                        printf("Digite o valor de C:\n");
                        scanf("%f", &c);

                        delta = pow(b, 2) - (4 * a * c);
                        if(delta >= 0){

                        printf("O valor de Delta é: %.2f.\n", delta);
                    

                        x1 = ( -b + sqrt(delta) ) / (2 * a);

                        x2 = ( -b - sqrt(delta)) / (2 * a);

                        printf("Valor de X1 = %.2f\n", x1);
                        printf("Valor de X2 = %.2f\n", x2);}
                        else{
                            printf("Impossível calcular pois o valor de Delta é negativo.\n");
                        }
                        


                    
                        break;

                    default:
                        printf("Opção inválida.\n");
                        break;
                }

                printf("\nVoltando ao menu principal...\n\n");
                break; // Saia do loop da calculadora e volte ao menu principal
            }
}else if(menu1 == 2){//menu questoes matematicas
    printf("Bem vindo ao treinamento de questões de matematica!\n\a");
    printf("Para começar digite 1.\n");
    scanf("%d", &menu2);

      if(menu2 == 1){
        printf("\nMário pretende realizar uma viagem utilizando um veículo cujo consumo médio de combustível é de 10 Km/L. Sabendo que percorrerá 300 000 m, é correto afirmar que o volume de combustível a ser consumido será de:\n");
        printf("\nDigite a resposta abaixo:\n");
        scanf("%lf", &S);}
        do{ if(S == 30){
            acertos++;
            printf("resposta correta!\n");
            printf("numero de acertos %d\n\n", acertos);

        }
        if(S != 30){
            printf("Resposta errrada, tente novamente!\n");
            printf("Digite nova resposta:\n");
            scanf("%lf", &S);
            if(S == 30){
                acertos++;
                printf("Resposta correta!\n");
                printf("Numero de acertos %d\n\n", acertos);
            }
        }
        

      }while(S != 30);

      
        printf("\nDuas empreiteiras farão conjuntamente a pavimentação de uma estrada, cada uma trabalhando a partir de uma das extremidades. Se uma delas pavimentar 2/5 da estrada e a outra os 81 km restantes, a extensão dessa estrada é de:\n");
        printf("\nDigite a resposta abaixo:\n");
        scanf("%lf", &S);

        do{ if(S == 135){
            acertos++;
            printf("Resposta correta!\n");
            printf("Numero de acertos %d\n", acertos);
        }

        if(S != 135){
            printf("Resposta errada, tente novamente!\n");
            printf("Digite nova resposta:\n");
            scanf("%lf", &S);
            if(S == 135){
                acertos++;
                printf("Resposta correta!\n");
                printf("Numero de acertos %d\n", acertos);
            }
        }


      }while(S != 135);

      printf("\nCom a chegada do verão os clubes com piscina se preparam para receber muitos associados aos finais de semana. Em um clube foi realizada uma manutenção na piscina principal que possui a capacidade de 86 400 L, por isso teve de ser esvaziada. O tempo para enche-la com a vazão habitual é de três dias, mas como o clube está com urgência, a vazão será aumentada em seis vezes. Em quanto tempo a piscina estará cheia?\n");
      printf("\nDigite a resposta abaixo:\n");
      scanf("%lf", &S);

      do{
        if(S == 12){
            acertos++;
            printf("Resposta correta!\n");
            printf("Numero de acertos: %d\n", acertos);
         }

         if(S != 12){
            printf("Resposta incorreta, tente novamente!\n");
            printf("Digite a nova resposta:\n");
            scanf("%lf", &S);
            
              if(S == 12){
               acertos++;
                printf("Resposta correta!\n");
                printf("Numero de acertos:%d", acertos);

            }


         }

      }while(S != 12);

      printf("\nUm carro com flex consegue utilizar uma mistura de álcool e gasolina sem acarretar nenhum problema mecânico. Um condutor de um carro flex abasteceu 30 litros de combustível, misturando gasolina e álcool. Ele pagou um total de R$ 190,00. Neste posto, os preços da gasolina e do álcool são, respectivamente, R$ 8,00 e R$ 5,50. Quantos litros de cada combustível foram abastecidos?\n");
      printf("\nDigite a resposta:\n");
      scanf("%lf", &S);

      do{
        if(S == 10){
            acertos++;
            printf("Resposta correta!\n");
            printf("Numero de acertos:%d", acertos);
        }
        if(S != 10){
            printf("Resposta incorreta, tente novamente!\n");
            printf("Digite a nova resposta:\n");
            scanf("%lf", &S);
             
             if(S == 10){
                acertos++;
                printf("Resposta correta!\n");
                printf("Numero de acertos:%d", acertos);
             }
        }
      }while(S != 10);//fim matematica

} else if (menu1 == 3) { // Sair do programa
            printf("Saindo do programa...\n");
            break; // Sair do loop principal
        } else {
            printf("Opção inválida.\n");
            printf("Retornando...\n");
        }
    }
   

        
return 0;
}
