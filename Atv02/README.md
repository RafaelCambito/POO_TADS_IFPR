Atv02

Atividade proposta e código utilizado:

Atividade:
Crie uma classe em Java que realize cada uma das seguintes tarefas:

a) Exibir a mensagem "Informe um inteiro: ", deixando o cursor na mesma linha;
b) Atribuir o produto de variáveis b e c para a variável a;
c) Utilizar um comentário para afirmar que um programa executa um cálculo de exemplo de folha de pagamento.

//======================================= Código utilizado =======================================
import java.util.Scanner;

public class Atv02 {

    public static void main(String[] args) {
        System.out.print("Informe um inteiro: "); //A) Utilizado System.out.print para manter o cursor na mesma linha
        int b, c, a = 0; // B) a vai receber os valores de b e c. A começando com valor zero. Considere b como dias trabalhados e c como valor pago por dia.
        Scanner s = new Scanner(System.in);
        System.out.println("Digite a quantidade de dias trabalhados: ");
        b = s.nextInt();
        System.out.println("Digite o valor pago por dia: ");
        c = s.nextInt();
        a = b * c; //A recebe multiplicação de B e C.
        System.out.println("O valor total do salário é: " + a);
        
        //programa executa um cálculo simples de folha de pagamento
    }
}

//======================================= Fim do código =======================================
