# AnoBissexto
Programa verifica se ano é bissexto.

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

ENGLISH!!!
# LeapYear
Checks if the year is a leap year.


	import javax.swing.JOptionPane;

	public class Exercicio2AnoBissexto {

	public static void main(String[] args) {
		
		String get = JOptionPane.showInputDialog("Type a year:");
		Double year = Double.parseDouble(get);
		
		if (year % 4 == 0) {
			System.out.println("Leap Year.");
		}
		else {
			System.out.println("Not a Leap Year.");
		}
	    }
	}
