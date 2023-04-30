**Atv06**

- Atividade proposta:</br>
Dados os valores de um depósito fixo mensal e um montante desejado, crie uma classe para determinar quantos meses serão necessários para acumular o montante desejado, considerando juros mensais de 0,5%.</br>

- Realização da atividade:</br>
Criado nova classe chamada Atv06;</br>
Definido Scanner para usuário informar o valor do montante desejado e valor do deposíto que irá realizar mensalmente.</br>
Inserido print do resultado demonstrando o valor acumalado e a quantidade de meses para chegar ao valor.</br>


- Código utilizado:</br>

//==============================================================================</br>

import java.util.Scanner;

public class Atv06 {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);        
        System.out.println("Informe o valor que deseja depositar mensalmente: ");
        float depositoMensal = scanner.nextFloat();        
        System.out.println("Agora informe o valor total do montante desejado: ");
        float montanteDesejado = scanner.nextFloat();        
        float saldoAtual = 0;
        int meses = 0;        
        while (saldoAtual < montanteDesejado) {
            saldoAtual += depositoMensal;
            saldoAtual += saldoAtual * 0.005;
            meses++;
        }        
        System.out.println("Para chegar ao valor de" + montanteDesejado + "será preciso" + meses + "meses");        
        scanner.close();
        
    }
} 

//==============================Fim do código ==================================
