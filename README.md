# algoritmo-la
Valor desconto //

#include <stdio.h>
#include <math.h>
double valor,desc;

int main(){
    printf("Digite o valor do produto: ");
    scanf("%lf",&valor);
    printf("\nO valor do produto é R$%.2lf\n",valor);
if (valor>=100){
desc=valor*0.10;
valor=valor-desc;
printf("\nO valor deste produto com desconto é = R$%.2lf",valor);
    }
  else if(valor<100){
   desc=valor*0.05;
   valor=valor-desc;
   printf("\nO valor deste produto com desconto é = R$%.2lf",valor);
   }
 
    
    return 0;
}
    
