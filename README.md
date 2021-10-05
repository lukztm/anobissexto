# anobissexto
Programa verifica se ano é bissexto.

package controle;

import javax.swing.JOptionPane;

public class Exercicio2AnoBissexto {

	public static void main(String[] args) {
		
		String entrada = JOptionPane.showInputDialog("Insira um ano:");
		Double ano = Double.parseDouble(entrada);
		
		if (ano % 4 == 0) {
			System.out.println("Ano Bissexto.");
		}
		else {
			System.out.println("Ano não bissexto.");
		}
	}
}
