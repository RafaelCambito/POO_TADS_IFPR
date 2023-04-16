**Atv03**

**OBS = Consegui executar essa atividade normalmente em minha máquina utilizando o NetBeans, contudo ao executar no ambiente Jupyter disponibilizado pelo professor, ocorre o seguinte erro: ERROR: java.awt.HeadlessException: 
No X11 DISPLAY variable was set, but this program performed an operation which requires it.**

- Atividade proposta:</br>
Usando a classe JOptionPane para entrada de dados, crie uma classe que receba a nota de duas provas e de um trabalho. Calcule e mostre a média.

- Realização da atividade:</br>
Realizado import javax.swing.JOptionPane
Recebido valores das duas provas e realizado cálculo de média através da divisão dos valores recebidos pela quantidade de lançamentos.

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
