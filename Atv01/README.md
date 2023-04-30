**Atv01**

- Atividade proposta:</br>
Crie uma classe em Java que seja capaz de apresentar a soma de todos os argumentos inteiros ou reais recebidos. Argumentos inválidos devem ser desconsiderados sem provocar a exibição de erros ou  exceções.

- Realização da atividade:</br>
Criado nova classe chamada Atv01;</br>
Definido Scanner para usuário informar os valores</br>
Definido Scanner para usuário informar os valores</br>
Definido variável para soma dos valores</br>
Inserido print do resultado da soma.</br>

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
