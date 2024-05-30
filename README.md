/*
# C-activities
Exercícios iniciais de aprendizagem de C+
1) Sabendo que 100 quilowatts de energia custam um sétimo 
do salário mínimo, fazer um algoritmo que dados a valor 
do salário mínimo e a quantidade de quilowatts gastos por 
uma residência, exibir: valor em de cada quilowatt, valor 
da conta de energia e novo valor da conta de energia 
após um desconto de 10%.*/

#include <stdio.h>
#include <stdlib.h>

float salario, quilowatts1, quilowatts_gasto, conta1, conta2;

int main() {
	printf("Digite o valor do valor do salario mínimo\n");
	scanf("%f", &salario);
	printf("Quantidade de quilowatts gasto na residencia\n");
	scanf("%f", &quilowatts_gasto);
	quilowatts1=(salario/700);
	conta1=(quilowatts1*quilowatts_gasto);
	conta2=(0.9*conta1);
	printf("1 quilowatts equivalem a %f rais\n", quilowatts1);
	printf("A conta de energia é: %f reais\n", conta1);
	printf("A conta com desconto é: %f reais", conta2);
}
