 Atv01

Atividade proposta e código utilizado:

Atividade:
Crie uma classe em Java que seja capaz de apresentar a soma de todos os argumentos inteiros ou reais recebidos. Argumentos inválidos devem ser desconsiderados sem provocar a exibição de erros ou  exceções.

//======================================= Código utilizado =======================================
import java.util.Scanner;
import java.io.IOException;

public class Atv01 {

    public static void main(String[] args) throws IOException {
        double valor1, valor2, valor3, valor4, soma = 0; //Defini o input de 4 valores pelo usuÃ¡rio e variÃ¡vel soma para iniciar com o valor zerado. 
        Scanner s = new Scanner(System.in);
        System.out.println("Digite o primeiro valor: ");
        valor1 = s.nextDouble();
        System.out.println("Digite o segundo valor: ");
        valor2 = s.nextDouble();
        System.out.println("Digite o terceiro valor: ");
        valor3 = s.nextDouble();
        System.out.println("Digite o quarto e último valor: ");
        valor4 = s.nextDouble();
        soma = valor1 + valor2 + valor3 + valor4;
        System.out.println("A soma dos valores informados é: " + soma); // Soma dos valores serÃ¡ apresentada na tela com quebra de linha.
    }
}

//======================================= Fim do código =======================================
