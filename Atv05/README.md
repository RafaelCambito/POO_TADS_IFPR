**Atv05**

- Atividade proposta:</br>
Adicione a Atv04 (sem alterar as linhas que já existem) o cálculo para a média mensal de gastos, criando uma variável mediaMensal junto com uma mensagem. Para isso, concatene a String com o valor, usando "Valor da média mensal = " + mediaMensal.</br>

- Realização da atividade:</br>
Criado nova classe chamada Atv05;</br>
Utilizado código da Atv04, adicionando a variável mediaMensal e função para cálculo da média mensal.</br>
Inserido print do resultado da média mensal.</br>


- Código utilizado:</br>

//==============================================================================</br>

public class Atv05 {


   public static void main(String[] args) { //</br>
        double gastosJaneiro = 30000.00;//</br>
        double gastosFevereiro = 33030.77;//</br>
        double gastosMarco = 23899.01;//</br>
        double gastosTrimestre = gastosJaneiro + gastosFevereiro + gastosMarco;//</br>
        double mediaMensal = gastosTrimestre / 3; // Variável mediaMensal recebe gastosTrimestre e divide pela quantidade de meses.//</br>
        System.out.println("Total de gastos no trimestre = R$ " + gastosTrimestre);//</br>
        System.out.println("Valor da média mensal: R$ " + mediaMensal);//</br>
        
    }
}

//==============================Fim do código ==================================
