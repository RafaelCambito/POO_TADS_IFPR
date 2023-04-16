**Atv04**

- Atividade proposta:</br>
Atualmente os gastos mensais de uma empresa são feitos em planilhas eletrônicas. Assim, para fechar o balanço do primeiro trimestre, é necessário somar o gasto total. Sabendo que, em janeiro, foram gastos R$ 30.000,00 reais, em fevereiro, R$ 33.030,77 reais e em Março, R$ 23.899,01 reais, faça uma classe em Java que calcule e exiba o gasto total no trimestre, seguindo os seguintes passos:</br>

a) Crie uma classe chamada BalancoTrimestral com o método main;</br>
b) No método principal, declare uma variável chamada gastosJaneiro e inicialize-a com o valor gasto no mês de janeiro;</br>
c) Crie também as variáveis gastosFevereiro e gastosMarco, inicializando-as com os respectivos gastos, utilize uma linha para cada declaração;</br>
d) Crie uma variável chamada gastosTrimestre e inicialize-a com a soma das outras variáveis;</br>
e) Exiba a variável gastosTrimestre.</br>

- Realização da atividade:</br>
Criado classe BalancoTrimestral definida como main;</br>
Criado variáveis gastosJaneiro, gastosFevereiro e gastosMarco recebendo os valores repassados no exercício.</br>
Criado variavél para receber os gastos do trimestre e posteriormente print do resultado.</br>


- Código utilizado:</br>

//==============================================================================</br>

public class BalancoTrimestral {

    public static void main(String[] args) {
        double gastosJaneiro = 30000.00;
        double gastosFevereiro = 33030.77;
        double gastosMarco = 23899.01;
        double gastosTrimestre = gastosJaneiro + gastosFevereiro + gastosMarco;
        System.out.println("Total de gastos no trimestre = R$ " + gastosTrimestre);
    }
}

//==============================Fim do código ==================================
