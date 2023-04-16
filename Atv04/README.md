**Atv04**

- Atividade proposta:</br>
Atualmente os gastos mensais de uma empresa são feitos em planilhas eletrônicas. Assim, para fechar o balanço do primeiro trimestre, é necessário somar o gasto total. Sabendo que, em janeiro, foram gastos R$ 30.000,00 reais, em fevereiro, R$ 33.030,77 reais e em Março, R$ 23.899,01 reais, faça uma classe em Java que calcule e exiba o gasto total no trimestre, seguindo os seguintes passos:

a) Crie uma classe chamada BalancoTrimestral com o método main;
b) No método principal, declare uma variável chamada gastosJaneiro e inicialize-a com o valor gasto no mês de janeiro;
c) Crie também as variáveis gastosFevereiro e gastosMarco, inicializando-as com os respectivos gastos, utilize uma linha para cada declaração;
d) Crie uma variável chamada gastosTrimestre e inicialize-a com a soma das outras variáveis;
e) Exiba a variável gastosTrimestre.

- Realização da atividade:</br>
Criado classe BalancoTrimestral definida como main;
Criado variáveis gastosJaneiro, gastosFevereiro e gastosMarco recebendo os valores repassados no exercício.
Criado variavél para receber os gastos do trimestre e posteriormente print do resultado.


- Código utilizado:</br>

//==============================================================================</br>

import javax.swing.JOptionPane;

public class Atv03 {

    public static void main(String[] args) {
        String primeira_prova = JOptionPane.showInputDialog("Informe a nota da primeira prova: "); // Recebe o valor referente a nota da primeira prova
        double primeira_nota = Double.parseDouble(primeira_prova);
        String segunda_prova = JOptionPane.showInputDialog("Informe a nota da segunda prova:"); // Recebe o valor referente a nota da segunda prova
        double segunda_nota = Double.parseDouble(segunda_prova);
        String trabalho = JOptionPane.showInputDialog("Digite a nota do trabalho:"); // Recebe a nota do trabalho.
        double nota_trabalho = Double.parseDouble(trabalho);
        double media = (primeira_nota + segunda_nota + nota_trabalho) / 3; // Cálcudo de média dos valores. Soma os valores e divide pela quantidade de lançamentos
        JOptionPane.showMessageDialog(null, "A média é: " + media); // Mostra o resultado da média. Utiliza-se o método showMessageDialog de JOptionPane.
    }
}

//==============================Fim do código ==================================
